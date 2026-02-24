# Contact Dataset

Subject: ETL (Extract, Transform, Load) and CSV Data Parsing  
Name: Abdanur

## 📌 Project Description
This project reads user data from a text file (CSV-like lines), converts each line into a `Users` object, and then filters users by age range.  
It also includes simple error handling for missing files and unexpected errors.

## 💡 Features
- Read a file line-by-line using `try/except`
- Show a clear message if the file is not found
- Create a `Users` class with:
  - first name, last name, birth year, email
  - `getAge()` method (based on year 2023)
- Convert each row into an object and store them in a list
- Filter users by age range (`low=30`, `high=50`) and print:
  - email, age

## 📦 Technologies
- Python
- Jupyter Notebook (`.ipynb`)

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/MnstrsParago/ETL.CSV.ContactsDataset.git
   cd ETL.CSV.ContactsDataset
   ```

2. Open the notebook:
   - `Mini project 1.ipynb` (main logic)
   - or `DataParsing.ipynb` (additional parsing work)

3. Run all cells in Jupyter Notebook (VS Code / Jupyter / Colab).

## 📘 Reflection
This project helped me practice working with file input, handling errors, using classes, and filtering structured data.  
It also shows a basic ETL-style workflow: extract data from a file, transform it into objects, and load it into a list for processing.
