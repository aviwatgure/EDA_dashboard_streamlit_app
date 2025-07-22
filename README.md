# 📊 Automated EDA (Exploratory Data Analysis) Dashboard

This is a Streamlit-based web application that automates the process of Exploratory Data Analysis. The app provides an interactive interface for users to upload their datasets and perform comprehensive data analysis without writing any code.

## 🌟 Features

- **File Upload Support**: 
  - Supports multiple file formats (CSV, Excel, JSON, TXT)
  - Automatic file type detection and processing

- **Basic Information**:
  - Dataset shape and size
  - Preview of first and last few rows
  - Detailed information about data types and memory usage

- **Missing Values Analysis**:
  - Detection of missing values
  - Visual representation of missing value distribution
  - Percentage of missing values per column

- **Categorical Data Analysis**:
  - Frequency tables
  - Bar charts and pie charts
  - Distribution visualization for categorical variables

- **Numerical Data Analysis**:
  - Statistical summaries
  - Distribution plots (histograms with density curves)
  - Box plots for understanding data spread

- **Outlier Analysis**:
  - Detection of outliers using IQR method
  - Visual representation through box plots
  - Outlier statistics and percentages

- **Bivariate Analysis**:
  - Relationship analysis between two variables
  - Different plot types based on data types:
    - Numerical vs Numerical: Scatter plots with correlation
    - Numerical vs Categorical: Box plots
    - Categorical vs Categorical: Grouped bar charts

- **Multivariate Analysis**:
  - Correlation matrix heatmap
  - Detailed correlation values
  - Pair plots for numerical variables

## 🚀 Installation

1. Clone this repository:
   ```bash
   git clone [your-repo-url]
   cd EDA_automation_repo
   ```

2. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```

## 💻 Usage

1. Start the Streamlit app:
   ```bash
   streamlit run EDA_automation_app.py
   ```

2. Open your web browser and navigate to the displayed URL (typically `http://localhost:8501`)

3. Use the sidebar checkboxes to select which analyses you want to perform:
   - Basic Info
   - Missing Value Analysis
   - Categorical Analysis
   - Numerical Analysis
   - Outlier Analysis
   - Bivariate Analysis
   - Multi-variate Analysis

4. Upload your dataset using the file uploader in the sidebar

5. Explore different visualizations and analyses by interacting with the various options provided

## 📦 Dependencies

- streamlit
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn

## 🤝 Contributing

Feel free to fork this repository and submit pull requests. You can also open issues for bugs or feature requests.

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👥 Authors

curious_avi

## 🙏 Acknowledgments

- Streamlit team for their amazing framework
- The data science community for inspiration and support
