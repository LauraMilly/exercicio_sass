# 🎨 SASS Conversion Project

## 📁 Project Structure

```bash``
exercicio/
│
├── index.html            🌐 # Main page of the project
│
├── src/
│   └── sass/             ✨ # SASS source files
│       ├── global.scss   🌍 # Global styles for the project
│       ├── header.scss   🏷️ # Styles for the header section
│       ├── main.scss     📄 # Main styles for the page
│       ├── mixins.scss   🔧 # SASS mixins used across the project
│       ├── products.scss 🛍️ # Styles for the products section
│       ├── style.scss    🎨 # Main SASS file that imports other SASS files
│       └── variables.scss 🌈 # Variables like colors, fonts, etc.
│
├── style/
│   ├── style.css         🖌️ # Compiled CSS file from SASS
└── README.md             📖 # Project documentation


## 📝 Description

This project involves converting a basic CSS project to SASS by utilizing variables, mixins, and modularizing the styles into separate SASS files. The goal is to improve maintainability, scalability, and flexibility, making it easier to manage and update the project's styles in the future.

## 🔧 Steps Taken in the Project

1. **Folder Structure**:
    - SASS files are organized within the `src/sass/` directory, while the compiled `style.css` is placed in the `style/` folder.

2. **Files Created/Modified**:
    - **Variables**: The `variables.scss` file holds reusable variables (such as colors, font stacks) to ensure consistent styling across the project.
    - **Global Styles**: The `global.scss` file sets the base styles (e.g., body font, background colors).
    - **Component Styles**: The `header.scss` and `products.scss` files are responsible for styling specific sections of the website.
    - **Main Styles**: The `main.scss` file serves as the entry point for all styles, importing other SASS files to generate the final `style.css`.

3. **SASS Compilation**:
    - The SASS files are compiled into a single `style.css` file using the `sass --watch` command.
    - The compiled CSS file is placed in the `style/` folder.

4. **Version Control**:
    - The project has been initialized as a Git repository and pushed to GitHub.

## 🚀 How to Run the Project

1. **Install SASS** (if not already installed):

    ```bash
    npm install -g sass
    ```

2. **Compile the SASS**:

    To compile the SASS files into CSS, run the following command in the terminal:

    ```bash
    sass --watch src/sass/style.scss:style/style.css
    ```

    This command will watch for changes in the `style.scss` file inside the `src/sass/` folder and compile them into the `style/style.css` file.

3. **View the Project**:

    Open the `index.html` file in your browser to view the project.

## 🤝 How to Contribute

1. Fork this repository.
2. Create a new branch for your changes: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m "Description of changes"`.
4. Push your branch to GitHub: `git push origin feature-name`.
5. Create a pull request for review.

---

## 🔧 **Technologies used**:
- SASS (Syntactically Awesome Stylesheets)
- Git and GitHub for version control
