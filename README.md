# PaddleOCR-InvoiceDetection

### Project Title
Automated Receipt Detection Using Neural Networks and PaddleOCR

### The Application
The application aims to develop an automated system for detecting and extracting information from receipts using PaddleOCR. The system will streamline the process of handling receipts by accurately identifying and extracting key details such as receipt number, date, total amount, and vendor information from scanned or digital receipts.

Benefits of this solution? This solution will benefit businesses, accounting departments, and financial institutions that handle a large volume of receipts. Automating the receipt processing will reduce manual effort, minimize errors, and increase efficiency in financial operations.

### State of the Art Existing Solutions
Several solutions have been developed to address the problem of receipt detection and data extraction. Notable ones include:
Tesseract OCR: An open-source OCR engine that has been used in various applications for text extraction.
Google Cloud Vision API: A cloud-based solution that provides powerful OCR capabilities for detecting and extracting text from images.

### Differentiation from Current State of the Art
While existing solutions typically rely on off-the-shelf OCR engines or pretrained models, our approach involves building neural networks from scratch tailored for receipt-specific text detection and information extraction. Additionally, we will customizing the models to the structured format of receipts and incorporating advanced techniques, such as YOLOv9 for object detection and PaddleOCR for text recognition, we aim to achieve higher accuracy and efficiency in extracting key information like receipt numbers, dates, total amounts, and vendor details. This approach ensures a more robust and tailored solution for automated receipt analysis compared to general-purpose OCR solutions.

### Dataset

The dataset contains 973 scanned receipts. For each receipt you have an .jpg file of the scanned receipt, a .txt file holding OCR information and a .txt file holding the key information values.

Source- https://www.kaggle.com/datasets/urbikn/sroie-datasetv2/data

### Inputs and Outputs 
Inputs - Scanned or digital images of receipts.

Outputs - Extracted text data, including receipt number, date, total amount, and vendor information.

Intermediate Outputs -Detected text regions within the receipt images.

### References
• Liao, M., Shi, B., & Bai, X. (2018). TextBoxes++: A Single-Shot Oriented Scene Text Detector. IEEE Transactions on Image Processing, 27(8), 3676-3690.

• R. Bi, T. Xu, M. Xu and E. Chen, ”PaddlePaddle: A Production-Oriented Deep Learning Platform Facilitating the Competency of Enterprises,” 2022 IEEE 24th Int Conf on High Performance Computing & Communications; 8th Int Conf on Data Science & Systems; 20th Int Conf on Smart City; 8th Int Conf on Dependability in Sensor, Cloud & Big Data Systems & Application (HPCC/DSS/SmartCity/DependSys), Hainan, China, 2022, pp. 92-99, doi: 10.1109/HPCC-DSS-SmartCity-DependSys57074.2022.00046.

