# Student Performance Analysis with Python

This project conducts a descriptive statistical analysis of a student performance dataset using Python, Pandas, and Jupyter Notebook. The primary goal is to identify patterns related to attendance, study time, and final grades to inform and improve academic support strategies.

This project was developed as a practical exercise to apply and learn data analysis concepts.

---

## Key Analyses & Features

The analysis is structured into several key tasks as outlined in the main notebook `HU_SM4_01_Canedo_Miguel.ipynb`:

*   **Task 1: Initial Data Exploration**: Loading the dataset and performing an initial selection of relevant columns.
*   **Task 2: Data Quality Check**: Identifying and removing duplicate records, validating data ranges (grades 0-20), and detecting outliers in absences and final grades using the IQR method.
*   **Task 3: Basic Performance Indicators**: Calculating core metrics such as the average, minimum, and maximum final grade (`G3`), student counts by study time, and the overall average of absences.
*   **Task 4: Complementary Indicators**: Creating derived metrics, including the percentage of approved vs. failed students, categorizing absences into levels (Low, Medium, High), and normalizing final grades using Min-Max scaling.
*   **Final KPI Report**: Generating a summary of key business metrics, including:
    *   Average absences per age group.
    *   Total student count by sex.
    *   Comparison of final grades for students with high vs. low study time.
    *   Full distribution of final grades (min, max, mean, median).

---

## Dataset

The project uses the `student-mat.csv` dataset, which contains academic and demographic information for students in a mathematics course.

---

## Technologies Used

*   **Python 3**
*   **Pandas**: For data manipulation and analysis.
*   **NumPy**: For numerical operations, especially for conditional column creation.
*   **Jupyter Notebook**: For interactive analysis and reporting.

---

## Setup and Installation

To run this analysis on your local machine, please follow these steps.

**Prerequisites:**
*   Python 3.x installed
*   Git installed

**1. Clone the repository:**
```bash
git clone https://github.com/Elimge/students-stats.git
``` 
**2. Navigate to the project directory:**
```bash
cd students-stats
``` 
**3. Create and activate a virtual environment:**
*   On macOS/Linux
```bash
python3 -m venv venv
source venv/bin/activate
``` 
*   On Windows
```bash
python -m venv venv
.\venv\Scripts\Activate.ps1
``` 
**4. Install the required dependencies:**
With the virtual environment active, install all necessary libraries from the requirements.txt file.
```bash
pip install -r requirements.txt
``` 

## How to Run the Analysis
1.  Ensure your virtual environment is active.
2.  Start Jupyter Notebook from the terminal:
```Bash
jupyter notebook
```
3.  Your web browser will open a new tab. From there, navigate to and open the HU_SM4_01_Canedo_Name.ipynb file to view and run the analysis.

Alternatively, you can open the project folder in an editor like Visual Studio Code with the Jupyter extension installed and run the notebook cells directly from the editor.

## Author 
* Miguel Canedo Vanegas
* @Elimge on Github 
* Email: elimge@outlook.com