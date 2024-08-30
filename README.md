# Certificate Generator

This project is a GUI-based application that automates the generation of certificates using data from an Excel file and a Word template. The application is built using Python with the Tkinter library for the GUI and utilizes libraries such as Pandas, python-docx, and docx2pdf.

## Features

- **Excel Integration**: Select an Excel file containing names and other relevant data to be included in the certificates.
- **Customizable Templates**: Choose a Word document as a template for the certificates. The placeholders in the template are dynamically replaced with the data from the Excel file.
- **Multiple Output Formats**: Generate certificates in PDF or DOCX format.
- **User-Friendly Interface**: Easy-to-use graphical interface to select files, columns, and formats.

## Requirements

Before you begin, ensure you have the following installed:

- **Python 3.x**
- **pip (Python package installer)**

The following Python libraries are required:

- `pandas`
- `python-docx`
- `docx2pdf`
- `tkinter` (comes pre-installed with most Python distributions)

You can install these dependencies using the following command:

```bash
pip install pandas python-docx docx2pdf
```

Alternatively, you can install all dependencies listed in the `requirements.txt` file:

```bash
pip install -r requirements.txt
```

## Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/your-username/certificate-generator.git
   cd certificate-generator
   ```

2. **Install dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the application**:

   ```bash
   python certificate_generator.py
   ```

## Usage

1. **Select Excel File**: Click the "Select Excel File" button to choose an Excel file containing the data for the certificates.

2. **Select Template File**: Click the "Select Template File" button to choose a Word document as the template for the certificates.

3. **Select Columns**: Choose the appropriate columns from the Excel file to match the placeholders in the template.

4. **Select Output Format**: Choose the output format (PDF or DOCX) for the certificates.

5. **Generate Certificates**: Click the "Generate Certificates" button to start the process. The certificates will be generated and saved in the `certificates/` directory.

## Example

Here’s an example of how your Excel file and Word template might look:

- **Excel File**:
  - `Name`: Column containing names of recipients.
  - `Course`: Column containing the course details.
  - `Date`: Column containing the date of issue.

- **Word Template**:
  - Use placeholders like `{{Name}}`, `{{Course}}`, and `{{Date}}` in your template where you want the corresponding data to appear.

## Application Download

If you prefer not to run the application from the source code, you can download the compiled version directly. Please request access to the application by visiting the following Google Drive link:

[**Download Application**](https://drive.google.com/drive/folders/1JAjMK9dF1Nvheqe2FvmXVDn0Mves_Ssk?usp=sharing)

Once you’ve requested access, it will be granted within 24 hours.

## Contributing

If you would like to contribute to this project, feel free to fork the repository and submit a pull request. Please ensure that your contributions adhere to the coding standards and guidelines of the project.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

If you have any questions or suggestions, feel free to open an issue or contact me directly at [jrkesari@gmail.com].
