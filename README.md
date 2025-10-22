This project is a simple web-based Captcha solver interface. It displays a static image captcha and provides an input field for the user to enter the text they see in the image. Upon submission, it validates the input against a predefined correct answer and shows a success or failure message.The project is built with HTML and JavaScript, using Tailwind CSS for styling to provide a clean and responsive user experience.

### Features:

*   Displays a captcha image (static `sample.png` by default).
*   Allows dynamic captcha image loading via URL parameter.
*   Input field for captcha text.
*   Client-side validation of the entered text.
*   Success/error messages based on validation.
*   Responsive design using Tailwind CSS.

### How to Run:

1.  **Save the files:** Save the `index.html` file and the `sample.png` image in the same directory.
2.  **Open in Browser:** Open the `index.html` file using any web browser (e.g., Chrome, Firefox, Safari).
3.  **Solve Captcha:** Type the text "ADUR3" (case-insensitive) into the input field and click "Submit".

### Customizing the Captcha:

*   **Change `sample.png`:** Replace the `sample.png` file with your desired captcha image. Make sure the new image is also named `sample.png`.
*   **Change Correct Answer:** Modify the `correctCaptchaText` variable in the JavaScript section of `index.html` to match the text of your new captcha image.
*   **Dynamic Image Loading:** You can specify a captcha image URL using the `url` query parameter in the browser. For example:
    `http://localhost:8000/index.html?url=https://example.com/your-captcha-image.png`
    (Note: This will only work if the image URL is accessible and adheres to CORS policies if loaded from a different origin).

### Technologies Used:

*   HTML5
*   CSS3 (Tailwind CSS)
*   JavaScript (ES6+)

### Project Structure:

*   `index.html`: The main HTML file containing the structure, styling, and JavaScript logic.
*   `sample.png`: The default captcha image.

### Future Improvements (Possible):

*   Implement server-side captcha generation and validation.
*   Add a "Refresh Captcha" button.
*   Introduce different types of captchas (e.g., arithmetic, audio).
*   Enhance accessibility features.
