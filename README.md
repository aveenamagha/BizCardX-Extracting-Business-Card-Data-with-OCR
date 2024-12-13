# Overview
This project is a Streamlit application that allows users to upload an image of a business card and extract relevant information from it using the easyOCR library. The extracted information includes the company name, cardholder name, designation, mobile number, email address, website URL, area, city, state, and pin code. Users can also save the extracted information along with the uploaded business card image into a database.

# How It Works

Business Card Upload:

The card is uploaded and saved to a predefined location on the system.
OCR is applied to read text from the image.

Extracted text is processed to identify relevant fields (e.g., email, phone number, company name


Image Processing:

Detected text is highlighted on the uploaded image using OpenCV.
Displays a preview of the processed image in the app.

Data Upload:

Data extracted from the card is stored in a MySQL database with the associated card image in binary format.

Data Management:

Users can view, edit, or delete card details via the "Update and Delete" section.
Screenshots

1. Home Page: Displays a sample business card and lists the technologies used.
   
2. Upload and Extract: Users can upload a card and view extracted data.
  
3. Data Management: Allows users to modify or delete existing card information.

 
# Technologies Used


Frontend: Streamlit

Backend: EasyOCR, OpenCV, Python

Database: MySQL

Libraries: Pandas, Matplotlib, PIL


# Future Enhancements


Add support for additional languages in OCR.

Enhance data extraction logic for better accuracy.

Implement advanced search and filter options for stored business cards.

Allow multiple card uploads in one session.

  











