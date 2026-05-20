<div align="center">

# <span style="color:#3b82f6">Supervised Spatial Estimation (Linear Regression Models)</span>

![Python](https://img.shields.io/badge/Python-3.10%2B-1e293b?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit_Learn-Machine_Learning-f7931e?style=for-the-badge&logo=scikit-learn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-Computation-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557c?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-059669?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-3b82f6?style=for-the-badge)

<br/>

<h3>
  <em>"Mapping Continuous Target Vectors via Ordinary Least Squares and Orthogonal Feature Fitting"</em><br/>
</h3>

<br/>

[📌 Overview](#-overview) • [✨ Features](#-features) • [🚀 Pipeline Flow](#-pipeline-flow) • [⚙️ Installation](#%EF%B8%8F-installation) • [🧠 Mathematical Foundations](#-mathematical-foundations) • [🤝 Contributing](#-contributing)

</div>

---

## 📌 Overview

**Supervised Spatial Estimation** is a foundational machine learning repository that implements **Ordinary Least Squares (OLS) Linear Regression** to map continuous numeric target variables based on single-variable feature inputs. Processing structural property areas (*Square Footage*), this pipeline optimizes a trend boundary to output price estimations.

By fitting weights using matrix formulations, the system determines optimal feature slopes, handles incoming custom inference metrics ($1100\text{ sq ft}$), and renders a clear scatter canvas displaying real metrics, model boundaries, and isolated targeted inferences.

---

## ✨ Features

### 🎯 Core Capabilities
| Feature | Description |
|---|---|
| 📐 **Feature Space Matrix Vectorization** | Formats structural feature values using NumPy to run fast algebraic estimations. |
| 📈 **Ordinary Least Squares Optimization** | Evaluates and minimizes model residual squares to align the trend boundary. |
| 🔮 **Isolated Inference Prediction** | Inputs unseen numeric metrics into the trained model to yield instant estimations. |
| 🎨 **Dynamic Regression Dashboard** | Renders custom Matplotlib canvases mapping data markers alongside target predictions. |
| 🏁 **Subtle Grid Matrix Rendering** | Generates a tracking background map to make graph intersections easily scannable. |

### 🌟 Design Highlights
- 🧠 **Supervised Learning Blueprint** — Evaluates explicitly defined training matrices ($X \rightarrow y$) to discover structural relationship slopes.
- ⚡ **Near-Instant Mathematical Inference** — Built on Scikit-Learn's lightweight, highly optimized algebraic fitting code frameworks.
- 📉 **Continuous Target Production** — Outputs non-discrete numerical predictions instead of class labels, making it ideal for valuation systems.

---

## 🚀 Pipeline Flow

┌─────────────────────────────────────────────────────────┐│               STRUCTURAL FEATURE INGESTION              ││       (Input Matrices: Area Mapping vs Target Valuations)│└─────────────────────────────────────────────────────────┘│▼[ Multi-Dimensional Matrix Vectorization ]│▼┌───────────────────────────────────────────────────────┐│               ORDINARY LEAST SQUARES FIT              ││    Compute Residual Bounds ──► Extract Feature Weight  │└───────────────────────────┬───────────────────────────┘│▼[ Deploy Trained Regression Target Line Boundary ]│▼┌───────────────────────────────────────────────────────┐│             TARGET INFERENCE EVALUATION               ││    Process Unseen Sample (1100) via Linear Equations  │└───────────────────────────┬───────────────────────────┘│▼┌─────────────────────────────────────────────────────────┐│                 VISUAL REGRESSION MATRIX                ││                                                         ││   Render: Matplotlib 2D Linear Coordinate System Scatter││   Line: Optimized trend slope capturing feature patterns││   Marker: Highlighted point marking target prediction  │└─────────────────────────────────────────────────────────┘
---

## ⚙️ Installation

### Prerequisites

Make sure your local computer has these foundational software components set up:
- Python 3.10+
- Git

---

### 🔧 Step-by-Step Setup

**1. Clone the Repository**
```bash
git clone [https://github.com/jaweriashakoor/Continuous-Price-Prediction-LinearRegression.git](https://github.com/jaweriashakoor/Continuous-Price-Prediction-LinearRegression.git)
cd Continuous-Price-Prediction-LinearRegression
2. Create a Virtual EnvironmentBashpython -m venv myenv

# Windows (PowerShell)
.\myenv\Scripts\Activate.ps1

# Linux / macOS
source myenv/bin/activate
3. Install DependenciesBashpip install numpy scikit-learn matplotlib
4. Execute the Estimation ScriptBashpython linear_regression_prediction.py
🧠 Mathematical FoundationsThe Core Linear EquationThe single-variable linear regression model expresses the relationship between our input feature ($x$) and the target continuous variable ($y$) using a straight-line equation:$$y = \beta_0 + \beta_1 x + \epsilon$$Where:$\beta_1$ represents the feature slope (the weight/impact of square footage on valuation).$\beta_0$ represents the y-intercept (the base baseline valuation).$\epsilon$ represents the statistical noise or residual errors.Minimizing the Cost FunctionTo locate the absolute best trend line, Scikit-Learn minimizes the Residual Sum of Squares (RSS). This cost equation aggregates the squared differences between actual recorded values ($y_i$) and the model's projected estimations ($\hat{y}_i$):$$RSS = \sum_{i=1}^{n} (y_i - \hat{y}_i)^2$$By solving for the exact weights where the derivative of this loss reaches zero, this script establishes a highly accurate projection boundary to evaluate future property spaces.🤝 ContributingContributions help keep our open-source tools robust, optimized, and ready for development!Bash# 1. Fork the Project Repository
# 2. Setup your feature branch
git checkout -b feature/gradient-descent-comparison

# 3. Commit functional updates
git commit -m "Add: Implement manual gradient descent tracking comparisons"

# 4. Push updates to origin branch
git push origin feature/gradient-descent-comparison

# 5. Open a Pull Request
📄 LicenseThis analysis pipeline is distributed as open-source software under the terms of the MIT License.
