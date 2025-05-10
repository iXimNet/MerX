# Mermaid Diagram Online Renderer (MerX)

MerX is a web-based tool that allows you to render diagrams from Mermaid syntax and export them as PNG or SVG files. It provides a simple and intuitive interface for quickly visualizing and sharing your Mermaid diagrams.

## Features

-   **Live Mermaid Rendering**: Input your Mermaid code and see the diagram render in real-time.
-   **Export to PNG**: Download your diagram as a high-quality PNG image.
-   **Export to SVG**: Download your diagram as a scalable SVG vector graphic.
-   **Interactive Preview**: View your diagram in a modal with zoom-in and zoom-out capabilities.
-   **Responsive Interface**: The application is designed to work seamlessly across different screen sizes.
-   **Error Handling**: Provides feedback for invalid Mermaid syntax.

## Technologies Used

-   HTML
-   CSS (Tailwind CSS)
-   JavaScript
-   Mermaid.js (v10)

## How to Use

1.  **Open `default.html` in your web browser.**, or try https://ixim.com.cn/merx directly.
2.  **Enter Mermaid Syntax**: Type or paste your Mermaid diagram code into the input text area on the left.
3.  **Generate Diagram**: Click the "生成图表" (Generate Diagram) button.
4.  **View Diagram**: The rendered diagram will appear in the panel on the right.
5.  **Export**:
    *   Click "导出 PNG" (Export PNG) to download the diagram as a PNG file.
    *   Click "导出 SVG" (Export SVG) to download the diagram as an SVG file.
6.  **Preview**: Click on the rendered diagram to open it in a larger preview modal. Use the "+" and "-" buttons or mouse wheel to zoom.

## Setup (for Development)

This project primarily uses client-side technologies and does not require a complex build process for its core functionality.

1.  **Clone the repository (if applicable).**
2.  **Ensure you have a modern web browser.**
3.  **Tailwind CSS (Optional - for development):**
    *   If you want to modify styles and use Tailwind CSS, you'll need Node.js and npm installed.
    *   Install dependencies:
        ```bash
        npm install
        ```
    *   To compile Tailwind CSS during development (watch for changes):
        ```bash
        npx tailwindcss -i ./src/input.css -o ./main.css --watch
        ```
    *   To build Tailwind CSS for production:
        ```bash
        npx tailwindcss -i ./src/input.css -o ./main.css --minify
        ```
    *   The `main.css` file is already included, so you can run `default.html` directly without needing to compile Tailwind unless you make style changes.

## Project Structure

-   `default.html`: The main HTML file for the application.
-   `main.css`: Compiled Tailwind CSS styles.
-   `src/input.css`: Source CSS file for Tailwind processing.
-   `tailwind.config.js`: Configuration file for Tailwind CSS.
-   `package.json`: Lists development dependencies (Tailwind CSS).
-   `.gitignore`: Specifies intentionally untracked files for Git.
-   `README.md`: This file.
