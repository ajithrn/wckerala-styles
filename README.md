# WordCamp Kerala - Site Styles

This repository contains the CSS and Sass files for the official website of WordCamp Kerala. These files are responsible for styling the website's frontend.

## Installation

1. Clone the repository to your local machine:

   ```shell
   git clone https://github.com/ajithrn/wckerala-styles.git
   ```
   
2. Navigate to the project directory:

   ```shell
   cd wckerala-styles
   ```

3. Install the required dependencies:

   ```shell
   npm install
   ```

## Usage

1. **Development:**

   During development, you can make changes to the Sass files and use the provided build tools to compile them into CSS.

   - Modify the Sass files located in the `src` directory.
   - To compile the Sass files into CSS, run the following command:

     ```shell
     npm run build
     ```

     The compiled CSS file will be available in the `dist` directory.

   - Alternatively, you can use the following command to automatically rebuild the Sass files whenever changes are detected:

     ```shell
     npm run watch
     ```

2. **Deployment:**

   When deploying the website, make sure to use the compiled CSS file located in the `dist` directory.

## Contributing

1. Fork the repository.
2. Create a new branch for your changes: `git checkout -b feature/your-feature-name`.
3. Commit your changes: `git commit -m "Add your commit message"`.
4. Push to the branch: `git push origin feature/your-feature-name`.
5. Create a pull request.

Please ensure that your contributions adhere to our [Code of Conduct](CODE_OF_CONDUCT.md). Also, make sure to follow our [Contributing Guidelines](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).