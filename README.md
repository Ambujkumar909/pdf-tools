# PDF Tools

## Overview

PDF Tools is a Flask-based web application designed to handle various PDF operations, such as merging, splitting, and converting PDF files into other formats like Word, Excel, and PowerPoint. The application provides a user-friendly interface and integrates CSS styling for an enhanced visual experience.

---

## Features

- **Merge PDFs:** Combine multiple PDF files into one.
- **Split PDFs:** Extract specific pages from a PDF into a new file.
- **Convert PDFs:** Convert PDF files to Word, Excel, or PowerPoint formats.

---

## File Structure

The project files are organized as follows:

### Backend

- **`app.py`****\*\*\*\*\*\*\*\*:** The main Flask application file that handles routing and backend logic.

### Templates (HTML Files)

- **`index.html`****\*\*\*\*\*\*\*\*:** The homepage of the application.
- **`convert.html`****\*\*\*\*\*\*\*\*:** Page for selecting and performing PDF conversion operations.
- **`merge.html`****\*\*\*\*\*\*\*\*:** Page for merging multiple PDFs.
- **`split.html`****\*\*\*\*\*\*\*\*:** Page for splitting a PDF into smaller parts.
- **`result.html`****\*\*\*\*\*\*\*\*:** Page for displaying the results of operations.

### Static (CSS Files)

- **`style.css`****\*\*\*\*\*\*\*\*:** Custom CSS file for styling the application.

---

## How to Run the Application

1. **Prerequisites:**

   - Ensure you have Python installed on your system.
   - Install Flask using the command:
     ```bash
     pip install flask
     ```

2. **Setup:**

   - Place all files (`app.py`, `index.html`, `convert.html`, `merge.html`, `split.html`, `result.html`, `style.css`) in the appropriate folders:
     - `app.py` should remain in the root directory.
     - Create a folder named `templates` and move all HTML files into it.
     - Create another folder named `static` and move `style.css` into it.

3. **Run the Application:**

   - Open a terminal in the project directory and run:
     ```bash
     python app.py
     ```
   - Access the application in your web browser at `http://127.0.0.1:5000/`.

---

##

---

## Future Enhancements

- Add more PDF tools like compression and password protection.
- Integrate a database for saving user data and histories.

---

## License

This project is licensed under the terms described in MIT license. Ensure you include and abide by the license.

---

