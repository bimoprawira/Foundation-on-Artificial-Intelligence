# Foundation-on-Artificial-Intelligence
Ch. 1: Foundation on Artificial Intelligence (First Team Project at Startup Campus)

# I Want to Withdraw All My Savings in Cash!
Program ini dirancang untuk membantu bank dalam melikuidasi seluruh tabungan nasabah dalam bentuk tunai berdasarkan permintaan. Program ini menggunakan denominasi uang kertas dan koin yang umum di Indonesia, dan akan mengalokasikan uang dari denominasi terbesar ke terkecil untuk mencapai jumlah yang diminta. Jika terdapat jumlah sisa yang tidak dapat dicairkan karena keterbatasan denominasi, program akan menginformasikannya kepada pengguna.

## Fitur

 - Input Integer: Program menerima input integer dari pengguna, yaitu jumlah tabungan nasabah yang ingin dicairkan (dalam rupiah).
 - Validasi Maksimum: Program membatasi input hingga maksimal 1 miliar rupiah.
 - Informasi Sisa yang Tidak Dapat Dicairkan: Jika terdapat jumlah yang tidak dapat dicairkan, program akan menampilkan jumlah tersebut.

## Program Rules
- Bank harus memprioritaskan pecahan terbesar terlebih dahulu untuk ditampilkan.
- Jika terdapat saldo yang tidak dapat dicairkan, bank harus menginformasikannya.
- Bank harus menghitung berapa jumlah Uang Kertas dan Uang Logam yang dibutuhkan.
- Bank hanya dapat mencairkan uang dengan jumlah maksimal 1 miliar Rupiah
- Program tidak bisa menerima input selain integer (float, string, dll)

# 2. Data Analysis & Visualization

This project aims to analyze an HR dataset created by Dr. Carla Patalano, which is used in the graduate MSHRM course called HR Metrics and Analytics at New England College of Business. The analysis will answer various data aggregation questions, conduct exploratory data analysis (EDA), and create predictive models to understand the factors influencing employee termination.

---

- **Task Analysis** :
  - **Salary Statistics by Marital Status and Gender**: Calculate the minimum, median, maximum, and average salary for employees based on marital status and gender using the `agg()` function.
  - **Top-5 Reasons for Termination**: Identify the five most common reasons for employee termination.
  - **Performance by Recruitment Source**: Determine which recruitment source has the highest number of employees who "Exceeds" the performance score. Apply a filter for performance score and use sort_values() for sorting.
  - **Manager Count by Department**: Count the number of unique managers in each department using nunique() as the aggregation function.
  - **Termination Ratio by Gender**: Calculate the termination ratio by gender.
  - **Relationship Between Manager and Performance Score**: Analyze whether there is a relationship between an employee's manager and their performance score.
  - **Best Recruiting Sources for Low Termination Ratio**: dentify the best recruitment sources to ensure a low ratio of employee termination.

- **Visualizations** :
  1. Scatter Plot: A scatter plot of "Salary" vs. "EngagementSurvey" with different colors representing termination status ("Termd").
  2. Bar Chart: Visualize the number of terminations per department.
  3. Pie Chart: Display the percentage of terminated employees by position.
  4. Boxplot: Create a boxplot showing salary distribution by marital status and differentiate it by termination status.
  5. Pairplot: Generate a pairplot comparing 'Salary', 'EngagementSurvey', 'EmpSatisfaction', and 'Absences' with color coding based on termination status ("Termd").
  
---
## Running the Notebooks

1. Open [Google Colab](https://colab.research.google.com/) and upload the `.ipynb` files.
2. Or you can click on the "`Open in Colab`" button at the top of the project on GitHub.
