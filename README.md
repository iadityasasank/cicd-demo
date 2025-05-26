# GitHub CI/CD Demo

This is a simple demonstration project showing how to implement CI/CD with GitHub Pages. The project consists of a static website that is automatically deployed when changes are pushed to the main branch.

## Project Structure

- `index.html` - Main webpage
- `styles.css` - Styling for the webpage
- `.github/workflows/` - Contains GitHub Actions workflow files (to be added)

## Setting Up GitHub Pages

1. Go to your repository settings
2. Navigate to "Pages" under "Code and automation"
3. Under "Source", select "Deploy from a branch"
4. Choose "main" branch and "/ (root)" folder
5. Click "Save"

## Local Development

To test the website locally, you can use any simple HTTP server. For example:

- Using Python:
  ```bash
  python -m http.server 8000
  ```
- Using Node.js:
  ```bash
  npx http-server
  ```

Then open your browser and navigate to `http://localhost:8000`

## Making Changes

1. Clone the repository
2. Make your changes to the HTML or CSS files
3. Commit and push to the main branch
4. GitHub Actions will automatically deploy your changes
5. Wait a few minutes and check your GitHub Pages URL

## Features

- 🚀 Automatic deployment to GitHub Pages
- ✨ Modern, responsive design
- 🔍 Simple and clean code structure
- 📱 Mobile-friendly layout

## Contributing

Feel free to fork this repository and submit pull requests to contribute to this demo project.

## License

This project is open source and available under the MIT License. 