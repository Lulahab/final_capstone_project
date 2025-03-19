# 📊 YouTube Analysis Project

A data analysis project that examines YouTube video statistics using Python and Jupyter Notebooks. The goal is to identify trends in video performance, including views, likes, and engagement rates.

## 🚀 Features
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Visualization of trends using Matplotlib & Seaborn
- Insights and recommendations for content strategy

## 📥 Installation
To set up the project locally:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Lulahab/final_capstone_project.git
   ```
2. **Navigate to the project folder:**
   ```bash
   cd final_capstone_project
   ```
3. **Create a virtual environment (optional but recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # For Mac/Linux
   venv\Scripts\activate     # For Windows
   ```
4. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
5. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```
6. **Open and run** `notebooks/youtube_analysis.ipynb`

## 📂 Project Structure
```
📁 final_capstone_project
│-- 📁 data
│   ├── ANF_sales_data.xlsx
│-- 📁 notebooks
│   ├── youtube_analysis.ipynb
│-- requirements.txt
│-- README.md
```

## 🔄 Project Workflow
### 1️⃣ Data Collection
- **YouTube Data:** Collected using the YouTube API.
- **Google Trends Data:** Fetched from Google Trends.
- **Sales Data:** Extracted from Abercrombie & Fitch records.

### 2️⃣ Data Cleaning
- Removed missing values and duplicates.
- Standardized column names and formats.
- Resampled time-series data for consistency.

### 3️⃣ Data Merging
- Combined data from different sources (YouTube, Google Trends, Sales) into a single dataset.
- Aligned timestamps to ensure accuracy.

### 4️⃣ Exploratory Data Analysis (EDA)
- Analyzed trends in video views, likes, and engagement rates.
- Explored correlations between Google Trends, YouTube engagement, and sales.

### 5️⃣ Data Visualization
- Created interactive charts using Matplotlib & Seaborn.
- Visualized trends over time and relationships between variables.

### 6️⃣ Key Findings & Insights
- Identified patterns between YouTube engagement and brand sales.
- Found trends that suggest social media presence impacts business performance.

## 🛠️ Technologies Used
- **Python** 🐍
- **Pandas** for data manipulation
- **Matplotlib & Seaborn** for visualization
- **Jupyter Notebook** for interactive analysis

## 📊 Data Sources
- **YouTube API or dataset from Kaggle**
- **Custom CSV or Excel files**

## 🤝 Contributing
Contributions are welcome! To contribute:
1. **Fork the repository**
2. **Create a new branch** (`git checkout -b feature-branch`)
3. **Commit your changes** (`git commit -m "Added a new feature"`)
4. **Push to the branch** (`git push origin feature-branch`)
5. **Open a Pull Request**

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📧 Contact
For questions, reach out at:
- **GitHub**: [Lulahab](https://github.com/Lulahab)
- **Email**: your-email@example.com
