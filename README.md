Power Transformer: Box-Cox & Yeo-Johnson with Linear Regression

📌 Overview

This project demonstrates the impact of data transformation techniques on model performance.
Using Box-Cox and Yeo-Johnson transformations, I improved the predictive performance of a Linear Regression model, with each transformation resulting in a higher R² score compared to the baseline.


---

🚀 Features

Box-Cox Transformation: Applied to stabilize variance and make data more normal distribution-like.

Yeo-Johnson Transformation: Similar to Box-Cox but works with both positive and negative values.

Linear Regression Model: Implemented after each transformation to track performance improvement.

Performance Tracking: R² score calculated for:

Original data (baseline)

After Box-Cox transformation

After Yeo-Johnson transformation




---

📊 Results

Transformation	R² Score

Original Data	baseline score
Box-Cox	score after Box-Cox
Yeo-Johnson	score after Yeo-Johnson


> ✅ In each case, the R² score increased, showing that proper transformations can significantly improve model accuracy.




---

🛠 Tech Stack

Python

Pandas

NumPy

Scikit-learn

Matplotlib (for visualization)



---

📂 Repository Structure

Power_Transformer/
│── Power_Transformer.ipynb     # Main notebook with transformations & model
│── README.md                   # Project documentation
│── requirements.txt            # Python dependencies


---

📖 How to Run

1. Clone the repository:

git clone https://github.com/Divyanshu-sharma-coder/Power_Transformer.git
cd Power_Transformer


2. Install dependencies:

pip install -r requirements.txt


3. Run the notebook:

Open Power_Transformer.ipynb in Jupyter Notebook or Google Colab.

Execute cells in order.





---

🎯 Key Takeaways

Data transformations like Box-Cox and Yeo-Johnson can boost model performance.

Always check R² score (or other metrics) before and after transformations.

Simple preprocessing can lead to significant accuracy 
