# Streamliner

Flask webapp that replaces words in uploaded docx files and outputs the new version. Useful if you want to quickly replace a dictionary of words. Streamliner was built for a debating website to reduce the number of syllables in a speech, but can be easily repurposed.

## Setup

### Dependencies

Streamliner was built on Python 2.7 and Flask. It uses the python-docx library, which can be easily installed with pip using `pip install python-docx`.

### Quickstart

1. Clone the project and enter the directory
2. `export FLASK_APP=app.py`
3. `flask run`

## TODO

1. Find way to re-render the index template after send_file. This would allow me to show the number of syllables saved via a flash.
