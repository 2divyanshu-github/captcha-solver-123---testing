# Captcha Solver UI

This is a simple, single-file responsive web application designed to help users "solve" captchas by providing an input field to enter the text displayed in an image. It's built using plain HTML, CSS (via Tailwind CSS CDN), and JavaScript.

## Features

- **Responsive Design**: Adapts to various screen sizes.
- **Dynamic Image Loading**: Loads captcha images from a URL parameter (`?url=...`) or defaults to a local sample image.
- **User Input Form**: Allows users to type in the perceived captcha text.
- **Basic Validation**: Provides feedback on whether the entered text matches a predefined "correct" answer for the default `sample.png`.

## Setup and Usage

1.  **Save the files**: Ensure `index.html` and `sample.png` are in the same directory.
2.  **Open `index.html`**: Simply open `index.html` in your web browser.

### Loading Custom Captcha Images

You can specify a captcha image URL by adding a `url` query parameter to the `index.html` URL.

**Example:**
`file:///path/to/your/index.html?url=https://example.com/some-captcha-image.png`

If no `url` parameter is provided, the application will default to displaying `sample.png`.

### Solving the Captcha

For the default `sample.png`, the correct text to enter is `ADUR3`. Enter this into the input field and click "Submit" to see the "Correct" message.

## Technologies Used

-   **HTML5**: Structure of the web page.
-   **Tailwind CSS (CDN)**: For responsive and utility-first styling.
-   **JavaScript**: For dynamic image loading and basic form interaction.

## License

This project is open-source and available under the MIT License. See the `LICENSE` file for more details.