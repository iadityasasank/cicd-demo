# GitHub CI/CD Demo

This is a simple demonstration project showing how to implement CI/CD with GitHub Pages. The project consists of a static website that is automatically deployed when changes are pushed to the main branch.

## Project Structure

- `index.html` - Main webpage
- `styles.css` - Styling for the webpage
- `.github/workflows/` - Contains GitHub Actions workflow files

## Setting Up GitHub Pages

1. Go to your repository settings
2. Navigate to "Pages" under "Code and automation"
3. Under "Source", select "Deploy from a branch"
4. Choose "main" branch and "/ (root)" folder
5. Click "Save"

## Local Development

### Starting the Local Server

You can use any of these methods to run the website locally:

1. **Using Python (Recommended)**:
   ```bash
   python -m http.server 8000
   ```
   Then open your browser and visit: `http://localhost:8000`

2. **Using Node.js**:
   ```bash
   npx http-server
   ```

3. **Using PHP**:
   ```bash
   php -S localhost:8000
   ```

### Stopping the Local Server

1. **Windows**:
   - Find the process using port 8000:
     ```bash
     netstat -ano | findstr :8000
     ```
   - Kill the process (replace PID with the number from above):
     ```bash
     taskkill /PID <PID> /F
     ```
   
2. **Linux/Mac**:
   - Press `Ctrl+C` in the terminal where the server is running
   - Or find and kill the process:
     ```bash
     lsof -i :8000
     kill -9 <PID>
     ```

### Troubleshooting

- If port 8000 is already in use, try a different port:
  ```bash
  python -m http.server 8080
  ```
- If you see "Address already in use", make sure to stop any existing servers first

## Making Changes

1. Clone the repository
2. Make your changes to the HTML or CSS files
3. Test locally using the steps above
4. Commit and push to the main branch
5. GitHub Actions will automatically deploy your changes
6. Wait a few minutes and check your GitHub Pages URL

## Features

- 🚀 Automatic deployment to GitHub Pages
- ✨ Modern, responsive design
- 🔍 Simple and clean code structure
- 📱 Mobile-friendly layout
- 🖥️ Easy local development setup

## Contributing

Feel free to fork this repository and submit pull requests to contribute to this demo project.

## License

This project is open source and available under the MIT License. 