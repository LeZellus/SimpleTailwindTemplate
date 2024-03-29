# Simple Tailwind Template

## Description

This project is a basic template for a website. It employs HTML, Tailwind, and JavaScript to create a simple yet extendable skeleton for web development. The project's architecture is designed to be intuitive and easy to customize.

## Project Structure

Here's the layout of the project:

- `index.html`: The main page of the site.
- `style/`: Folder containing the CSS files.
    - `app.css`: Contains custom styles for the site and tailwind import.
- `js/`: Folder containing the JavaScript scripts.
    - `app.js`: The main JavaScript file for the site's functionality.
- `images/`: Folder containing the Images files.

## Using Tailwind

This project uses [TailwindCSS](https://tailwindcss.com/) to manage css of the template.

## Fork the Project

Forking a project allows you to freely experiment with changes without affecting the original project. Here are the steps to fork this project:

1. **Log in to GitHub.** Make sure you have a GitHub account and are logged in.

2. **Navigate to the Repository.** Go to the main page of this repository.

3. **Fork the Repository.** In the top-right corner of the page, find and click the "Fork" button.

4. **Clone Your Fork.** After forking, you will be redirected to your fork. Clone it to your local machine by clicking on the "Code" button and copying the URL. Then, run the following command in your terminal:

    ```
    git clone <URL_OF_YOUR_FORK>
    ```

   Replace `<URL_OF_YOUR_FORK>` with the URL you just copied.

5. **Create a New Branch.** Navigate into the cloned directory and create a new branch for your changes:

    ```
    git checkout -b <your_new_branch_name>
    ```

   Replace `<your_new_branch_name>` with the name of your new branch.

6. **Make Your Changes.** You can now make changes to your forked version of the project.

7. **Push Changes to Your Fork.** After making your changes, commit them and push the changes to your fork:

    ```
    git add .
    git commit -m "Describe your changes here"
    git push origin <your_new_branch_name>
    ```

8. **Create a Pull Request.** If you want to contribute your changes back to the original project, go to your fork on GitHub, click on "Pull Request" and then on "New Pull Request" to start the process.

## Tailwind Installation and Setup

To use `tailwindcss` for automatically compiling your css files, you need to have Node.js installed and set up on your system. Here’s how you can do it:

### Step 1: Install Node.js

First, install Node.js from [Node.js official website](https://nodejs.org/). Download and run the installer for your operating system.

### Step 2: Initialize dependences

Navigate to your project directory in the command line and run the following command to initialize npm. This will create a `package.json` file in your project.

```bash
npm install
```

### Step 3: Run tailwind watcher node-sass

Now, run the following command on your project. This tool will help you to compile your css files to include tailwindcss classes.

```bash
npx tailwindcss -i ./style/app.css -o ./style/output.css --watch
```

## Contributing

Contributions to this project are welcome. If you wish to contribute, please follow these steps:

1. **Fork the project.** This will create a copy of the project on your GitHub account.

2. **Create a new branch.** This allows you to work on a new feature without affecting the main branch.

3. **Make your changes and commit them.**

4. **Submit a Pull Request.** Please clearly explain the changes made and their purpose.