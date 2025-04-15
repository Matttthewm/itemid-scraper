# ItemID Finder

This is a web scraping tool that allows users to input a URL from an auction website featuring an artwork and extract the following information:

* **Filename:** The filename of the main artwork image.
* **Title:** The title of the artwork.
* **Artist:** The name of the artist.

## Installation

1.  **Clone the repository** (if you are using Git).
    ```bash
    git clone <repository_url>
    cd scraper
    ```

2.  **Install the required Python packages.** Make sure you have Python and pip installed on your system.
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1.  **Run the Flask application.**
    ```bash
    python scraper.py
    ```
    This will start a development server (usually at `http://127.0.0.1:5000/`).

2.  **Open the `index.html` file in your web browser** or navigate to the server address provided in the previous step.

3.  **Enter the URL of artwork page** in the input field.

4.  **Click the "Find Info" button.**

5.  The extracted filename, title, and artist (if found) will be displayed below the input. Any errors during the process will be shown in the error section.
