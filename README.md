# BA_Bootcamp_8_GMM_Challenge

# Gaussian Mixture Model Challenge



# 🎯 Gaussian Mixture Model – Behavioral Segmentation Challenge

Welcome to the **Gaussian Mixture Model Challenge**, a hands-on project to explore the power of **unsupervised learning** through **Behavioral Segmentation**. In this challenge, you’ll dive into real-world customer data, apply **probabilistic clustering**, and generate actionable customer segments.

---

## 🧩 Challenge Overview

Most companies build value-based segmentation — but it doesn’t always reveal **who the customers truly are** or **how they behave**.

That’s where **Behavioral Segmentation** comes in. Your mission is to **uncover customer personas** using their actual transactional behavior.

---

## 🚀 Steps to Complete the Challenge

### 1️⃣ Prepare the Dataset

- Include all relevant dimensions for segmentation.
- Make sure all variables are in **numeric format** for the Gaussian Mixture Model (GMM) to work.
- Handle any missing values and clean the data accordingly.

> ✅ Dataset used: `CC GENERAL.csv`  
> 📄 Variable descriptions: `CC GENERAL data dictionary.docx`

---

### 2️⃣ Determine the Optimal Number of Clusters

- Use **AIC (Akaike Information Criterion)** and **BIC (Bayesian Information Criterion)** to evaluate the model.
- Lower values = better model fit.
- Plot AIC/BIC scores across a range of cluster numbers to decide the optimal count.

---

### 3️⃣ Build the Gaussian Mixture Model (GMM)

- Use the `sklearn.mixture.GaussianMixture` class.
- Fit the model to the dataset (excluding the `CustomerID` column).
- Predict customer clusters and assign them to the original dataset.

---

### 4️⃣ Interpret the Segments

- Analyze the **means of each cluster** to understand typical behavior.
- Assign meaningful names to each cluster.
- Get creative! Add labels that reflect customer lifestyles or spending behavior.

> 🧠 Example Segments:
> - Cluster 0: *Lower Middle Class*
> - Cluster 1: *Inactive*
> - Cluster 2: *High Rollers*
> - Cluster 3: *Conscious High Income*
> - Cluster 4: *Upper Middle Class*
> - Cluster 5: *Active Purchasers*

---

## 📁 Repository Structure

| File Name                                | Description                                       |
| ---------------------------------------- | ------------------------------------------------- |
| `Gaussian Mixture Model Challenge.ipynb` | Jupyter notebook with full implementation         |
| `Gaussian Mixture Model Challenge.pdf`   | Challenge instructions and explanation            |
| `CC GENERAL.csv`                         | Credit card dataset for behavioral segmentation   |
| `CC GENERAL data dictionary.docx`        | Column descriptions and data context              |
| `README.md`                              | Project overview and instructions (this file)     |

---

## 🛠️ Tools & Libraries Used

- `Python 3`
- `NumPy`, `Pandas`, `Matplotlib`
- `scikit-learn`: for Gaussian Mixture Models

---

## 📊 Output Highlights

- 📉 AIC/BIC curve to select optimal clusters
- 🏷️ Clustered customer segments
- 🧾 Segment interpretations based on feature averages
- 💬 Meaningful and creative segment names

---

## 🧠 What You'll Learn

- Unsupervised Learning with GMM
- Dimensionality Preparation
- Model Evaluation with AIC/BIC
- Customer Segmentation Interpretation
- Real-World Data Cleaning & Analysis

---

## 👋 Final Note

This project bridges theory and real-world application. Whether you're a data science beginner or sharpening your clustering skills, this challenge provides a complete end-to-end learning experience in **behavioral analytics**.

> Feel free to fork, explore, and contribute! 🚀  
> ⭐ Star the repo if you found it helpful.

---


