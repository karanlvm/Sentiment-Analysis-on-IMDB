## Overview
This project includes two types of Jupyter notebooks:
1. **Stable.ipynb** 
2. **Peak.ipynb**

Each of these notebooks serves a specific purpose and provides insights into different aspects of the model's performance during the training process. Below is an explanation of each notebook and its intended use.

---

## Notebooks Description

### 1. **Stable.ipynb**
The `Stable.ipynb` notebook represents the **stable version** of the model. This version has been optimized to ensure **consistent and reproducible results**. When you run this notebook, you can expect to achieve a reliable accuracy across multiple runs, which makes it ideal for evaluating the overall performance of the model in a controlled, repeatable manner. The stable version is often tuned for robustness and generalization, ensuring that it performs well across a variety of test cases without extreme fluctuations.

- **Use case**: Ideal for evaluating the general performance and stability of the model.
- **Output**: Provides consistent accuracy and validation metrics over multiple runs.

---

### 2. **Peak.ipynb**
The `Peak.ipynb` notebook represents the **peak version** of the model. In this version, we have fine-tuned the model to achieve its **peak accuracy**, which may not be consistently reproducible across runs due to slight variations in training or validation conditions. However, this notebook provides the highest observed performance in terms of accuracy and other evaluation metrics, such as precision, recall, and F1 score.

- **Use case**: Best for identifying the model’s potential in achieving the highest accuracy and other performance metrics.
- **Output**: Displays the peak accuracy and other metrics, though it may have slight variability across runs.

---

## WandB Report
For a more in-depth analysis of the project, including performance metrics, hyperparameter tuning, and visualizations, please refer to the [WandB Report](insert-link-here). This report offers detailed insights into the training process, the model’s behavior over time, and helps in understanding the effects of different hyperparameter configurations.

- **Link**: [WandB Report](https://api.wandb.ai/links/karanlvm123-ut-arlington-uta-the-university-of-texas-at-/vas9d2g9)
---

## Authors

- [Karan Vasudevamurthy](https://github.com/karanlvm)
- [Suraj Kalyampudi](https://www.github.com/SurajKalyampud)
- [Sai Krishna Movva Jaya](https://www.github.com/SKrishnaMJ)

