# 🛒 Customer Spending Behavior Analysis (AI/ML Task)

## 🎯 Project Goal  
This project conducts an exploratory data analysis (EDA) of customer spending behavior to understand product preferences, purchasing trends, and customer characteristics. The notebook also performs basic customer segmentation to group customers based on their spending patterns and derive actionable marketing insights.

---

## 🔬 Project Overview  

The notebook is organized into four main stages:

1. **Data Preparation**
   - Load the cleaned customer spending dataset.
   - Standardize numerical features to ensure proper scaling for clustering and visualization.

2. **Exploratory Data Analysis (EDA)**
   - General summary statistics and overview of key variables.
   - **Box Plot**: Purchase Frequency vs Purchase Amount.
   - **Pie Chart**: Product Category Preferences.
   - **Scatter Plot**: Income vs Purchase Amount.
   - **Count Plot**: Loyalty Status vs Promotion Usage.

3. **Customer Segmentation**
   - Cluster customers based on spending habits and related features.
   - Use standardized numerical features to identify distinct customer groups.

4. **Insights & Marketing Strategies**
   - Generate inferences from each visualization to understand customer behaviors.
   - Suggest targeted marketing strategies for:
     - Customer engagement
     - Retention
     - Promotions and campaign design

---

## 📊 Dataset  

- The dataset is provided via a link in the **“Dataset of Customer Spending Behavior”** section of the notebook.  
- It contains customer‑level information such as spending amounts, purchase frequency, product category preferences, loyalty status, and related attributes.

> You must download the dataset **locally** from the link in the **“Dataset of Customer Spending Behavior”** section and then upload it when prompted by the **Import Dataset** cell in the notebook.

---

## 📁 Project Structure  

- `README.md` → Project description and usage instructions (this file).  
- `customer_spending_eda.ipynb` (or similar) → Main notebook containing:
  - Dataset import logic  
  - EDA visualizations  
  - Clustering and customer segmentation  
  - Insights and marketing strategy notes  

---

## 🚀 How to Run (Google Colab Recommended)  

1. **Open the notebook in Colab**
   - Upload the `.ipynb` file to Google Drive and open it with **Google Colaboratory**, or  
   - Open it directly from GitHub using an “Open in Colab” link if available.

2. **Download and import the dataset**
   - In the notebook, locate the **“Dataset of Customer Spending Behavior”** section where the dataset link is provided.  
   - Click the link and download the dataset **to your local machine**.  
   - Run the **“Import Dataset”** cell:
     - When prompted, upload the downloaded dataset file.  
   - Once uploaded, the notebook will load the data and proceed to standardization and EDA.

3. **Run the notebook cells in order**
   - Run the **Data Preparation** section to:
     - Load the dataset.
     - Standardize numerical features.  
   - Run the **EDA** section to:
     - Generate summary statistics.
     - Produce box, pie, scatter, and count plots.  
   - Run the **Customer Segmentation** section to:
     - Perform clustering on customer spending behavior.  
   - Review the **Insights & Marketing Strategies** section for:
     - Interpretations of the clusters and plots.
     - Suggested marketing actions.

---

## 📄 Notes  

- All logic (EDA, clustering, plotting, and insights) is contained inside the notebook.  
- Any extra Python libraries (e.g., `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit‑learn`) are typically installed via `pip` commands within the notebook cells if needed.  
- Always ensure you upload the correct customer spending dataset when the **Import Dataset** cell prompts for a file.
