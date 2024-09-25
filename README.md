# Flask-Email-Sending-Application

This project is a simple example of an email sending application using Flask. It utilizes Flask-Mail for sending emails.

## Features

-   **Email Sending**: Sends emails based on the sender, recipient, and content provided by the user.

## Technologies Used

-   Python 3.10.12
-   Flask
-   Flask-Mail
-   Python-Dotenv (for managing environment variables)

## Installation and Execution

### 1. Clone the Project

```bash
git clone https://github.com/Tyrrnien81/Flask-Email-Sending-Application.git
cd Flask-Email-Sending-Application
```

### 2. Set Up a Virtual Environment

```bash
# Create a virtual environment
python -m venv venv

# Activate the virtual environment on Windows
venv\Scripts\activate

# Activate the virtual environment on MacOS/Linux
source venv/bin/activate
```

### 3. Install Required Packages

```bash
pip install flask flask-mail python-dotenv
```

### 4. Enter your gmail address & App password in the .env file

-   more info about App password: https://support.google.com/mail/answer/185833?hl=en

```bash
MAIL_SERVER = smtp.gmail.com
MAIL_PORT = 465
MAIL_USE_TLS = False
MAIL_USE_SSL = True
MAIL_USERNAME = example@gmail.com # Your gmail address
MAIL_PASSWORD = abcd efgh ijkl mnop # Your gmail App-password
```

### 5. Run the Application

```bash
python app.py
```

### 6. Access the Application

```bash
http://127.0.0.1:5000
```

## Usage

-   **Email Sending**: On the main page of the application, enter the sender's email, recipient's email, and the message content, then click the "Send" button to send the email.
-   **Recipient Management**: Multiple recipients can be entered by separating them with commas.
