# 📊 Braude Analyzer

A web-based Excel analysis platform that allows users to upload, preview, combine, compare, visualize, and export spreadsheet data through a simple and responsive interface.

Braude Analyzer was designed to make working with multiple Excel files easier for users who do not want to manually process or compare spreadsheet data.

---

## Overview

Braude Analyzer provides a collection of tools for working with Excel files directly from the browser.

Users can:

* Upload one or multiple Excel files
* Preview spreadsheet data
* Visualize columns using different chart types
* Combine selected columns from multiple files
* Compare files based on shared columns
* Download processed data as a new Excel file
* Switch between light and dark modes

The application focuses on making data analysis accessible through an easy-to-use visual interface.

---

## Main Features

### Excel File Upload

* Upload files using a file picker
* Drag and drop Excel files
* Upload multiple files
* Preview selected files
* Remove or replace files before processing
* Validate selected files before analysis

### Data Visualization

* Select an uploaded Excel file
* Choose columns for the X-axis and Y-axis
* Select from different chart types
* Generate visual representations of spreadsheet data
* Update visualizations based on selected columns

### File Combination

* Upload multiple Excel files
* Select columns from each file
* Preview selected data
* Combine information into one dataset
* Download the result as a new Excel file

### File Comparison

* Upload multiple Excel files
* Detect shared columns
* Compare file structures and data
* Preview rows from original files
* Show or hide original file data

### User Interface

* Responsive page layouts
* Drag-and-drop upload areas
* Navigation between analysis tools
* Light and dark themes
* Clear file previews
* Downloadable results

---

## Screenshots

### Home Page

The homepage introduces the platform and provides quick access to its main tools.

<img src="https://github.com/user-attachments/assets/5d47e753-78e4-4e62-a474-2dc48a05d92c" width="800" alt="Braude Analyzer homepage">

### Dark Mode

The application supports both light and dark themes.

<img src="https://github.com/user-attachments/assets/f8692a70-063a-41d1-a1d9-60aa57bcdfd0" width="800" alt="Braude Analyzer dark mode">

### Upload and Visualization

Users can upload Excel files, select data columns, and generate charts.

<img src="https://github.com/user-attachments/assets/21889772-1890-466c-93f6-e89e72f87bf5" width="800" alt="Excel upload page">

<img src="https://github.com/user-attachments/assets/396eb707-3909-4317-87c6-627759451c6f" width="800" alt="Excel data visualization">

### Combine Files

Users can select columns from multiple Excel files and export the combined result.

<img src="https://github.com/user-attachments/assets/617cefff-60ed-4f74-ad22-94a268d39a7e" width="800" alt="Combine Excel files page">

### Compare Files

The comparison page identifies shared columns and displays data from the uploaded files.

<img src="https://github.com/user-attachments/assets/34039830-9148-4051-b3c1-1179a8f1cf74" width="800" alt="Compare Excel files page">

### About Page

<img src="https://github.com/user-attachments/assets/5307f487-6e72-4399-bb42-0c3f45550196" width="800" alt="Braude Analyzer about page">

### Contact Page

<img src="https://github.com/user-attachments/assets/89ac741b-6b3e-48e7-9cec-efbd0dc8dfb9" width="800" alt="Braude Analyzer contact page">

---

## How It Works

### Visualize Excel Data

1. Open the Upload File page.
2. Upload an Excel file.
3. Select the file you want to analyze.
4. Choose a chart type.
5. Select the X-axis and Y-axis columns.
6. View the generated chart.

### Combine Excel Files

1. Open the Combine Files page.
2. Upload two or more Excel files.
3. Select the required columns from each file.
4. Preview the selected data.
5. Combine the files.
6. Download the generated Excel file.

### Compare Excel Files

1. Open the Comparison page.
2. Upload multiple Excel files.
3. View the shared columns detected by the application.
4. Display rows from the original files.
5. Compare the available data and structures.

---

## Technology Stack

Update this section so it matches the technologies actually used in the project.

| Technology     | Purpose                            |
| -------------- | ---------------------------------- |
| React          | User interface                     |
| JavaScript     | Application logic                  |
| HTML5          | Page structure                     |
| CSS3           | Styling and responsive design      |
| React Router   | Client-side navigation             |
| SheetJS / XLSX | Reading and generating Excel files |
| Chart library  | Data visualization                 |
| Vite           | Development and build tool         |

> Replace “Chart library” with the actual library used, such as Chart.js or Recharts.

---

## Project Structure

Update the folder names below if your project structure is different.

```text
src/
├── components/
│   ├── layout/
│   ├── navigation/
│   ├── fileUpload/
│   ├── filePreview/
│   └── charts/
├── pages/
│   ├── home/
│   ├── upload/
│   ├── combine/
│   ├── comparison/
│   ├── about/
│   └── contact/
├── services/
│   └── excelProcessing/
├── utils/
│   └── fileHelpers/
├── router/
├── App.jsx
└── main.jsx
```

---

## My Contribution

Braude Analyzer was developed as a project for processing and analyzing Excel files.

My contributions included:

* Building responsive application pages
* Implementing drag-and-drop Excel uploads
* Reading and previewing spreadsheet data
* Developing file-combination workflows
* Implementing comparison of shared columns
* Creating downloadable Excel results
* Adding data visualization functionality
* Building light and dark theme support
* Creating reusable frontend components
* Handling user input and file validation
* Debugging Excel-processing and display issues

> Keep only the items that accurately describe your personal work.

---

## Getting Started

### Prerequisites

Make sure the following are installed:

* Node.js 18 or newer
* npm

### Clone the Repository

```bash
git clone https://github.com/mhmdkh1905/Braude-Analyzer.git
cd Braude-Analyzer
```


### Install Dependencies

```bash
npm install
```

### Start the Development Server

```bash
npm run dev
```

Open the application at:

```text
http://localhost:5173
```

### Create a Production Build

```bash
npm run build
```

### Preview the Production Build

```bash
npm run preview
```

---

## Supported Files

The application is intended to work with Excel spreadsheet formats such as:

```text
.xlsx
.xls
```

Only keep both formats here if the application actually supports them.

---

## Future Improvements

* Add support for CSV files
* Add additional chart types
* Add advanced filtering and sorting
* Add spreadsheet data cleaning tools
* Add duplicate-row detection
* Improve handling of large Excel files
* Add clearer validation and error messages
* Add chart export as PNG or PDF
* Add saved analysis sessions
* Add automated tests
* Improve accessibility
* Improve mobile and tablet layouts

---

## Author

**Mohammad Khateeb**

* [GitHub](https://github.com/mhmdkh1905)
* [LinkedIn](https://www.linkedin.com/in/mohammad-khateeb-891332303)
* [Email](mailto:mhmd52kh@gmail.com)

---

## License

This project was developed for educational and portfolio purposes.
