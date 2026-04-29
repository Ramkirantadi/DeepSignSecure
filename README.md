# AI-Based Signature Verification

This project is an AI-based signature verification web application developed using Python and Flask. It uses machine learning techniques to analyze handwritten signatures and determine whether they are genuine or forged.

## Features

* Upload signature images
* AI-based verification of signatures
* Detection of genuine and forged signatures
* Simple and user-friendly interface
* Web-based application using Flask

## AI Integration

The system applies machine learning concepts to extract and compare signature patterns. Based on these patterns, the model classifies signatures as authentic or not.

## Project Structure

* app.py – Main Flask application
* templates/ – HTML files for UI
* static/ – CSS, JavaScript, and UI assets

## Important Note

To keep the repository lightweight and suitable for GitHub, the following components have been excluded:

* Signature dataset
* Trained AI model files
* Uploaded images (static/uploads)
* Local database files

These were removed using `.gitignore` since they are large in size and not required to understand the project code.

## How to Run

1. Install dependencies:
   pip install -r requirements.txt

2. Run the application:
   python app.py

3. Open in browser:
   http://127.0.0.1:5000/

## Conclusion

This project demonstrates how AI techniques can be integrated with web development to build a practical signature verification system.
