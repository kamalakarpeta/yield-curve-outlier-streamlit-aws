# Yield Curve Outlier Tool (Streamlit) on AWS EC2

**Description:**

Developed a Streamlit web application to identify and visualize outliers in yield curve data. The tool utilizes whisker plots and z-score calculations to detect potential data quality issues in newly constructed yield curves. Deployed the application on an AWS EC2 instance, making it accessible to users across the organization. This project significantly improved the efficiency and accuracy of yield curve validation.

**Key Technologies:**

* Python (Requests, Pandas, NumPy)
* Streamlit
* Matplotlib/Seaborn
* AWS EC2
* Web Server: **Nginx**
* Infrastructure as Code: **Terraform (for EC2 deployment)**
* SSH (for remote access)
* Version Control: **Git**

**Project Overview:**

* **Data Retrieval:** Implemented Python scripts using the `requests` library to fetch yield curve data from an internal API.
* **Data Processing:** Utilized `pandas` and `numpy` for data manipulation, cleaning, and calculation of z-scores.
* **Outlier Detection:** Employed statistical methods, including z-score analysis and whisker plots, to identify potential outliers in the yield curve data.
* **Interactive Visualization:** Developed an interactive Streamlit application to visualize yield curves and highlight detected outliers, allowing users to adjust parameters and explore the data.
* **Deployment on AWS EC2:** Deployed the Streamlit application on an AWS EC2 instance, ensuring accessibility for all team members.
* **Web Server Configuration:** Configured `Nginx` as a reverse proxy to handle incoming requests and route them to the Streamlit application.
* **Infrastructure as Code:** Used Terraform to automate the provisioning and configuration of the EC2 instance, enabling consistent and repeatable deployments.
* **Security:** Secured remote access to the EC2 instance using SSH and configured appropriate security groups.

**Key Achievements:**

* **Improved Data Quality:** Significantly enhanced the ability to identify and address data quality issues in yield curve data, leading to more accurate financial analysis.
* **Enhanced Efficiency:** Streamlined the outlier detection process, reducing the time required for manual validation.
* **Increased Accessibility:** Deployed the tool on AWS EC2, making it accessible to a wider audience within the organization.
* **Automated Deployment:** Implemented Infrastructure as Code using Terraform, enabling rapid and consistent deployments.
* **User-Friendly Interface:** Developed an intuitive Streamlit application that allowed users to easily visualize and analyze yield curve data.
* **Reduced Manual Effort:** Automated the process of outlier detection, thereby reducing the manual labor associated with data validation.

**Project Context:**

This project addressed the need for a more efficient and reliable method of validating newly constructed yield curves. By automating the outlier detection process and providing an interactive visualization tool, this project helped to improve the accuracy and efficiency of financial analysis.

**Contact:**

* LinkedIn: [URL](https://www.linkedin.com/in/kamalakarpeta/)
