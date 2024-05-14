# Classroom Borrowing System

This project is a Classroom Borrowing System designed for the Computer Information and Network Engineering Department. It provides an easy-to-use web interface for students and staff to borrow classrooms and supports multiple languages.

## Features
- User-friendly interface for borrowing classrooms
- Real-time data storage and retrieval using localStorage
- Multi-language support (Chinese, English, Vietnamese)
- Export borrowing data to Excel with password protection
- Automatic redirection to the default language page after inactivity

## Installation and Usage
1. Clone this repository to your local machine:
    ```bash
    git clone https://github.com/yourusername/classroom-borrowing-system.git
    ```
2. Navigate to the project directory:
    ```bash
    cd classroom-borrowing-system
    ```
3. Open `Chinese.html`, `English.html`, or `Vietnamese.html` in your preferred web browser.

## File Structure
- `Chinese.html`: Chinese version of the system
- `English.html`: English version of the system
- `Vietnamese.html`: Vietnamese version of the system
- `LOGO.png`: Favicon image for the web pages

## Usage
1. **Borrow a Classroom**:
    - Enter Student/Staff ID, Borrower's Name, select a Classroom, and Class Period.
    - Click the "Submit" button to save the borrowing information.
2. **Reset Form**:
    - Click the "Reset" button to clear the form fields.
3. **View Borrowing Data**:
    - All submitted borrowing records are displayed in a table below the form.
4. **Delete Borrowing Record**:
    - Click the "Delete" button to remove a specific borrowing record.
5. **Export to Excel**:
    - Click the "Export to Excel" button and enter the password `lhucin5701lhucin5701` to download the borrowing data as an Excel file.

## Contributing
1. Fork this repository.
2. Create a new branch:
    ```bash
    git checkout -b feature-branch
    ```
3. Make your changes and commit them:
    ```bash
    git commit -m "Add new feature"
    ```
4. Push to the branch:
    ```bash
    git push origin feature-branch
    ```
5. Open a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
