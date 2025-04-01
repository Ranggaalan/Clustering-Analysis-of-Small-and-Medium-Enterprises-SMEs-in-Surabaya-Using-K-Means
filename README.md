# **Clustering Analysis of Small and Medium Enterprises (SMEs) in Surabaya Using K-Means**  

📌 **Project Description**  
This project aims to segment Small and Medium Enterprises (SMEs) in Surabaya into two distinct clusters using the **K-Means clustering algorithm**. By analyzing various business characteristics, this segmentation provides insights into different SME profiles, which can aid policymakers, investors, and business owners in strategic decision-making.  
![image](https://github.com/user-attachments/assets/a94bb5a0-b82c-4ec1-a76d-9a75559d2955)


📝 **Dataset**  
**Source**: SME data from Surabaya  
**Features**:  
- **Industry Category** – Type of business sector  
- **Risk Level** – Business operational risk assessment  
- **Business Scale** – Small, medium, or microenterprise classification  
- **Number of Employees** – Total workforce in the SME  
- **Investment Amount** – Capital investment in the business  
- **Business Size** – Physical or operational scale of the industry  
- **Number of Enterprises** – Total count of SMEs in a category  
- **Type of Industry** – Specific sector classification  

🔍 **Methodology**  

📌 **Exploratory Data Analysis (EDA)**  
- Distribution analysis of SMEs across different features  
- Correlation heatmap to understand relationships between variables  
- Outlier detection and handling  

📌 **Data Preprocessing**  
- Handling missing values  
- Normalization and feature scaling  
- Dimensionality reduction (if necessary)  

📌 **Clustering Approach**  
✔ **K-Means Clustering** with **K = 2**  
✔ Optimal cluster validation using **Silhouette Score = 0.6**  
✔ Visualization of clustered SME groups  

📌 **Model Evaluation**  
- **Silhouette Score**: 0.6 (Indicates a moderate clustering structure)  
- Cluster distribution analysis  
- Business characteristics of each cluster  

📊 **Results**  
📌 **Cluster Insights**  
- **Cluster 1**: SMEs with **lower investment, smaller workforce, and lower risk levels**  
- **Cluster 2**: SMEs with **higher investment, larger workforce, and higher risk levels**  

📌 **Key Visualizations**  
- Cluster distribution plots  
- SME segmentation on feature space  
- Business characteristics per cluster  

![image](https://github.com/user-attachments/assets/cbdf2913-0061-466c-9799-c67fbf5d8189)

![image](https://github.com/user-attachments/assets/7728a422-8442-4ba8-9482-24fd4175e683)

### Cluster Results
![image](https://github.com/user-attachments/assets/d1ddf50b-40b6-4cc2-865b-24f3eaa679d7)

💻 **Technologies Used**  
- **Python**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **Machine Learning**: K-Means Clustering  
- **Evaluation Metrics**: Silhouette Score  

🔥 **Conclusion**  
This clustering analysis successfully segments SMEs in Surabaya into two groups based on key business characteristics. The **Silhouette Score of 0.6** suggests that the clustering model provides a meaningful segmentation, which can be leveraged for policy development, investment strategies, and business support initiatives.  
