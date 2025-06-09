
# Flask Data Summarizer

A simple Flask web application that allows users to input large blocks of text and generate concise summaries. The app supports customizable summary length and includes a loading screen for better user experience during processing.

---

## Features

- Input large text to generate a summary
- Adjustable summary length via slider
- Loading screen displayed while summary is generated
- Responsive, clean UI using Tailwind CSS and JavaScript
- Secure handling of API tokens via environment variables (recommended)

---

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/flask-data-summarizer.git
   cd flask-data-summarizer


2. (Optional) Create and activate a virtual environment:

   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Set your environment variables (e.g., for API tokens):

   * Create a `.env` file or export variables in your shell.

   Example `.env`:

   ```
   HUGGINGFACE_TOKEN=your_token_here
   ```

5. Run the Flask app:

   ```bash
   flask run
   ```

6. Open your browser and go to `http://127.0.0.1:5000`

---

## Usage

* Paste or type your text in the input box.
* Use the slider to select desired summary length.
* Click **Summarize**.
* Wait for the loading screen to disappear and see your summary below.

---


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

* Built using Flask, Tailwind CSS, and JavaScript.
* Inspired by the need for easy and fast text summarization.
