# Selenium-based PDF Reader

## Project Overview

This project, named PDFReader, focuses on automating PDF-related tasks using Selenium WebDriver and Apache PDFBox. It includes features for extracting images from PDFs, comparing images, and reading PDF content within a web browser.

## Project Structure

- **POM.xml**: Maven project configuration file specifying dependencies, including Selenium, TestNG, and PDFBox.
- **PDFReader.java**: Java class containing methods for extracting images from PDFs, comparing images, and reading PDF content.
- **PDFBrowserTest.java**: Test class using Selenium WebDriver to perform PDF-related tasks within a web browser, such as reading PDF content and extracting metadata.
- **PDFReaderTest.java**: Test class for PDFReader methods, including image extraction and comparison.
- **PDFEImageExtractor.java**: PDFStreamEngine extension for extracting images from PDFs using Apache PDFBox.

## Dependencies

- **Selenium WebDriver**: Automates browser interactions for PDF testing.
  - Version: 4.6.0
- **TestNG**: Testing framework for organizing and executing test cases.
  - Version: 6.14.3
- **PDFBox**: Library for working with PDF documents.
  - Version: 2.0.27

## Key Features

### Automated PDF Image Extraction

- Utilizes Selenium WebDriver and Apache PDFBox to automate the extraction of images from PDFs.
- Images are saved locally, enhancing the ability to compare and analyze them.

### Image Comparison

- Implements image comparison functionality to assess differences between two images.
- Calculates the percentage of difference, providing a quantitative measure.

### PDF Content Reading

- Uses Selenium WebDriver to navigate to a PDF link within a web browser.
- Extracts metadata and text content, demonstrating capabilities for reading PDFs in a browser environment.

### PDFBox Integration

- Integrates Apache PDFBox for low-level PDF processing, including image extraction and content reading.

## How to Use

1. Clone the repository.
2. Set up a Maven project in your preferred IDE.
3. Add the provided dependencies to the POM.xml file.
4. Run test classes using TestNG for automated PDF testing.

