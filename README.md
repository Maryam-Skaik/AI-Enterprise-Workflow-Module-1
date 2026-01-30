# AI Enterprise Workflow: Business Priorities and Data Ingestion

![IBM](https://upload.wikimedia.org/wikipedia/commons/thumb/5/51/IBM_logo.svg/2560px-IBM_logo.svg.png)

<br>

**Course:** [AI Workflow: Business Priorities and Data Ingestion](https://www.coursera.org/programs/artificial-intelligence-ai-enterprise-workflow-l2-ovjl6/learn/ibm-ai-workflow-business-priorities-data-ingestion)  
**Instructor:** IBM Digital Learning  
**Certificate:** [Verified Certificate on Coursera](https://www.coursera.org/account/accomplishments/verify/0SZHS1996DFQ)  

---

## Project Overview

This repository contains my final project for the **AI Workflow: Business Priorities and Data Ingestion** course offered by **IBM** through **Coursera**. The project demonstrates a comprehensive **data ingestion pipeline** for AI use cases, focusing on extracting, transforming, and cleaning data from **SQL databases** and **CSV files**. The goal is to prepare datasets for use in AI and machine learning models, with special emphasis on **business priorities**.

---

## Key Highlights

- **Data Ingestion** from both **SQL databases** and **CSV files**.
- **ETL Process** for cleaning and transforming data.
- Handling of large-scale datasets in **batches** to ensure optimal processing.
- Applied **quality assurance** checks, including missing data handling and duplicates removal.
- Final integration of multiple data sources into a **cleaned, ready-to-use dataset** for machine learning.

---

## Technologies Used

- **Python**  
- **Pandas**  
- **SQLite**  
- **NumPy**  
- **Matplotlib**  
- **Jupyter Notebooks**

---

## Getting Started

1. **Clone this repository**:

    ```bash
    git clone https://github.com/Maryam-Skaik/AI-Enterprise-Workflow-Module-1.git
    ```

2. **Install dependencies** (if you don’t have them already):

    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Jupyter Notebooks**:

    ```bash
    jupyter notebook
    ```

    Start with the **main notebook** that performs all steps of the data ingestion and transformation.

---

## Steps Performed

1. **Data Extraction**: 
   - Extracted data from an **SQLite database** containing customer, country, and invoice information.
   - Read **CSV files** for customer streams and subscription data.

2. **Data Cleaning**:
   - Removed duplicate customer entries.
   - Cleaned up missing values, especially for stream data.
   - Created new columns such as **age**, **customer_name**, and **subscription status**.

3. **Batch Processing**:
   - The project processes large datasets in **batches**, ensuring no data duplication and managing memory efficiently.
   - Used **batches** to run data ingestion steps on **smaller chunks** of data.

4. **Data Merging**:
   - Merged customer data with stream data and invoice data to create a **comprehensive dataset** ready for analysis.
   
5. **Final Output**:
   - **Cleaned data** saved as CSV files for later analysis or integration into AI models.

---

## How to Use

To run this project:

1. Ensure you have the required **Python libraries**.
2. Use the **ingestion functions** from the main notebook to process data from a **local SQLite database** and **stream CSV files**.
3. **Visualize and analyze** the results using **Pandas** or other **data science** tools.

---

## Quality Assurance

Throughout the process, **data quality checks** were implemented, including:

- **Handling missing data** by filtering out invalid records.
- **Removing duplicates** based on **customer_id**.
- **Ensuring data integrity** by merging datasets correctly.

---

## Future Improvements

This project can be extended by:

- Adding more sophisticated **data validation** (e.g., checking for outliers or errors).
- Implementing **real-time ingestion** pipelines using frameworks like **Apache Kafka**.
- Using **AI** to automate the detection of **data anomalies** during ingestion.

---

## IBM & Coursera

This project was created as part of **IBM's** **AI Workflow** course on **Coursera**, a hands-on learning experience focused on improving your **data ingestion** and **AI pipeline** skills.

Thank you to **IBM** for providing this learning opportunity!

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- [IBM AI Learning](https://www.ibm.com/training/)
- [Coursera](https://www.coursera.org/)
- [Pandas Documentation](https://pandas.pydata.org/pandas-docs/stable/)

