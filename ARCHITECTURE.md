# 🏗️ Project Architecture

This system is built for scalability, maintainability, and real-world use.

## 📁 Folder Structure
| Folder | Purpose |
|-------|--------|
| `notebooks/` | Exploratory analysis (Jupyter) |
| `src/` | Reusable Python functions (clean code) |
| `dashboard/` | Interactive Streamlit app |
| `data/` | Raw and processed datasets |
| `models/` | Saved forecasting models |
| `reports/` | PDFs for executives |
| `requirements/` | Dependencies for dev, prod, etc. |

## 🔄 Workflow
1. Load data → 2. Clean & explore → 3. Engineer features → 4. Train model → 5. Forecast → 6. Visualize

## 🚀 Design Principles
- **Modular**: Code can be reused or tested
- **Reproducible**: Anyone can run it
- **CFO-Ready**: Clear insights, not just charts