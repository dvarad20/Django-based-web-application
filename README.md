# Django-based-web-application-for-Data-Analysis

This is a Django-based web application that allows users to upload CSV files, perform data analysis using Pandas and NumPy, and display the results and visualizations on a web interface.

## Features

- **File Upload**: Upload CSV files for analysis.
- **Data Analysis**:
  - Display the first few rows of the data.
  - Calculate summary statistics (mean, median, standard deviation) for numerical columns.
  - Identify and handle missing values.
- **Data Visualization**: Generate and display histograms for numerical columns.

## Requirements

- Python 3.10
- Django 5.0.6
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Installation

1. **Clone the repository**:
    ```bash
    cd csv_analysis_project
    ```

2. **Create a virtual environment**:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. **Install dependencies**:
    ```bash
    pip install django
    pip install pandas numpy matplotlib seaborn
    ```

4. **Apply migrations**:
    ```bash
    python manage.py migrate
    ```

5. **Run the development server**:
    ```bash
    python manage.py runserver
    ```

6. **Access the application**:
    Open your web browser and go to `http://127.0.0.1:8000/`.

## Usage

1. **Upload a CSV file**:
   - Navigate to the home page.
   - Use the provided form to upload a CSV file.

2. **View Data Analysis**:
   - After uploading, view the first few rows of the data.
   - Check summary statistics, including mean, median, and standard deviation for numerical columns.
   - Identify missing values.

3. **View Data Visualization**:
   - A histogram for the first numerical column is generated and displayed.

## Project Structure

```
csv_analysis_project/
├── csv_analysis/
│   ├── migrations/
│   ├── static/
│   │   └── histogram.png
│   ├── templates/
│   │   └── csv_analysis/
│   │       └── home.html
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── forms.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   ├── views.py
├── csv_analysis_project/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
├── manage.py
├── .gitignore
├── requirements.txt
├── README.md
├── venv/
```

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Create a new Pull Request.


## Acknowledgements

- Django: https://www.djangoproject.com/
- Pandas: https://pandas.pydata.org/
- NumPy: https://numpy.org/
- Matplotlib: https://matplotlib.org/

- Seaborn: https://seaborn.pydata.org/
```


```
## Web Application Screen
![Screenshot (286)](https://github.com/dvarad20/Django-based-web-application-for-Data-Analysis/assets/157035521/18142695-9d59-409b-8f23-38a97c40865a)
![Screenshot (287)](https://github.com/dvarad20/Django-based-web-application-for-Data-Analysis/assets/157035521/cb1f8ca1-be8c-4ffc-90a5-2d224e16c3fb)
