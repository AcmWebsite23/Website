# Creating Virtual Environment
To install virtual environment:

'py -m pip install --user virtualenv'

Make a virtual env:

'python -m venv venv'

'.\venv\Scripts\activate'


# Switching from http to https
To do this, a ssl is required. Below is the format to acquire a personal ssl.

Navigate to the folder Website and open command line for the directory.

Pass the following command:

`openssl req -x509 -newkey rsa:4096 -nodes -out cert.pem -keyout key.pem -days 365`

# Dependencies
'Flask==2.3.2'