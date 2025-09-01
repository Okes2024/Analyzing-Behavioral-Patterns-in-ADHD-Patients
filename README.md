Analyzing Behavioral Patterns in ADHD Patients
📌 Overview

This project generates a synthetic dataset of ADHD vs. Control patients and applies data science and machine learning techniques to analyze behavioral, cognitive, and activity patterns. The pipeline includes descriptive statistics, clustering, PCA visualization, and Random Forest classification.

🚀 Features

Synthetic dataset generation (>100 samples) with realistic correlations

Demographics, attention, impulsivity, reaction times, and activity measures

Group-wise descriptive statistics with effect sizes

PCA for dimensionality reduction and visualization

KMeans clustering for unsupervised pattern discovery

Random Forest classification with accuracy, ROC AUC, and feature importances

Exportable dataset in CSV/Excel formats

📂 Project Structure
ADHD-Behavior-Analysis/
│── analyzing_behavioral_patterns_ADHD.py   # Main analysis script
│── ADHD_behavioral_synthetic_dataset.xlsx  # Example synthetic dataset
│── requirements.txt                        # Dependencies
│── README.md                               # Project documentation

🛠️ Installation

Clone the repository and install dependencies:

git clone https://github.com/your-username/ADHD-Behavior-Analysis.git
cd ADHD-Behavior-Analysis
pip install -r requirements.txt


Dependencies:

numpy

pandas

scikit-learn

matplotlib

📊 Usage
Generate Dataset & Run Analysis
python analyzing_behavioral_patterns_ADHD.py --n 600 --seed 42

Options

--n : number of samples (default 600, must be >100)

--seed : random seed for reproducibility

--no-plots : disable plotting

--out : output path for dataset (default: adhd_synthetic_dataset.csv)

📈 Example Output

Descriptive statistics with Cohen’s d effect sizes

Clustering table comparing true labels vs. KMeans clusters

Random Forest classification with accuracy and feature importances

Plots:

PCA scatter plot

Histograms of selected features

Feature importance bar chart

🤝 Contributing

Contributions are welcome! Please fork this repository, open an issue, or submit a pull request to suggest improvements or additional analyses.

📜 License

This project is licensed under the MIT License. See the LICENSE
 file for details.


 Author Name: Imoni Okes
 Github: @Okes2024
