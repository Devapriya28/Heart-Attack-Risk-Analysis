# Heart-Attack-Risk-Analysis

This project explores relationships between medical and lifestyle factors affecting heart attack risk.
It includes data preprocessing, statistical testing, and heatmap visualization of variable relationships.

## 📦 Requirements

pandas

scikit-learn

scipy

seaborn

matplotlib

## 🚀 Workflow

Load dataset (heart_attack_prediction_dataset.csv)

Encode categorical columns with LabelEncoder

### Apply statistical tests:

Continuous vs Continuous → T-test

Continuous vs Category → ANOVA

Category vs Category → Chi-square

## 📊 Output

The final result is a heatmap that shows how features are related:

1 → Weak/No relation

0 → Strong/Significant relation

This helps to quickly identify which factors influence each other.

Generate relationship matrix

Visualize with a heatmap
