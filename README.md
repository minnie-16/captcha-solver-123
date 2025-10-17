# Captcha Solver Frontend Application

This is a simple, single-page responsive web application designed to act as a frontend for a captcha solver. It displays a captcha image and provides an input field for the user to enter the text they see. The application supports loading captcha images from a URL parameter or defaulting to a local image.

## Features

-   **Responsive Design**: Built with Tailwind CSS for optimal viewing across various devices.
-   **Dynamic Image Loading**: Loads captcha images from a `url` query parameter (e.g., `?url=https://example.com/captcha.png`).
-   **Default Image**: If no `url` parameter is provided, it defaults to `sample.png`.
-   **User Input**: Allows users to type the perceived captcha text.
-   **Submission Feedback**: Provides basic feedback upon submission.

## Usage

To use this application, simply open `index.html` in your web browser.

### Loading a specific captcha image

You can specify a captcha image by appending a `url` query parameter to the `index.html` file in your browser's address bar:

`http://localhost:8000/index.html?url=https://your-domain.com/path/to/your/image.png`

(Replace `http://localhost:8000/` with the actual path to your `index.html` if serving it locally, or just open `file:///path/to/index.html?url=...`)

### Using the default captcha image

If no `url` parameter is provided, the application will display the `sample.png` image located in the same directory as `index.html`.

## Technologies

-   **HTML5**: Structure of the web page.
-   **Tailwind CSS**: For styling and responsiveness (via CDN).
-   **JavaScript**: For dynamic content, URL parameter parsing, and event handling.

## Local Development

1.  Save the `index.html`, `README.md`, and `LICENSE` files into a single directory.
2.  Ensure `sample.png` is also in the same directory.
3.  Open `index.html` in your web browser.

No build steps or server are required for this basic frontend application.