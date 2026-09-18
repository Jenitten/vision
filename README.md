\# Simple Flask Web Application



A minimal, single-file web application built using the \*\*Flask\*\* micro-framework in Python. This project serves as a starting point for understanding backend routing and local server setups.



\## Prerequisites



Before running the application, make sure you have \*\*Python 3\*\* installed on your computer.



\## Getting Started



Follow these steps to set up and run the application locally.



\### 1. Install Dependencies

Open your terminal or command prompt and install Flask using pip:

```bash

pip install flask

```



\### 2. Run the Application

Navigate to the directory containing `app.py` and execute the file:

```bash

python app.py

```

\*(Note: You may need to use `python3 app.py` depending on your operating system setup).\*



\### 3. Access the Web App

Once the server starts running, open your web browser and navigate to:

```text

http://127.0.0.1:5000

```



\## How It Works



\- \*\*`127.0.0.1` (Localhost):\*\* Points back to your own computer, keeping the server private and local.

\- \*\*Port `5000`:\*\* The default network port where Flask listens for incoming traffic.

\- \*\*`@app.route("/")`:\*\* Tells Flask to trigger the `home()` function whenever a user visits the main root URL, returning a basic HTML header string to the browser.



\## Stopping the Server

To shut down the local server, go back to your terminal window and press `Ctrl + C`.



