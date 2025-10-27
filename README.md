# Asteroid Hazard Classification for Planetary Defense

**Research Project:** Lightweight Machine Learning for Near-Earth Object Risk Assessment

## 🎯 Project Overview
Binary classifier to predict Potentially Hazardous Asteroids (PHAs) using orbital parameters, achieving planetary defense-grade accuracy while being 100x faster than deep learning approaches.

## 📊 Dataset
- **Source:** NASA Asteroids Classification (Kaggle)
- **Size:** 90,836 asteroids
- **Features:** Absolute magnitude, diameter, velocity, miss distance, eccentricity
- **Target:** Binary (hazardous: 9%, non-hazardous: 91%)

## 🚀 Quick Start

### Setup Environment
python3 -m venv asteroid_env
source asteroid_env/bin/activate
pip install -r requirements.txt
cat > requirements.txt << 'EOF'
# Core Data Science
numpy==1.24.3
pandas==2.0.3
scipy==1.11.1

# Machine Learning
scikit-learn==1.3.0
xgboost==1.7.6
imbalanced-learn==0.11.0

# Visualization
matplotlib==3.7.2
seaborn==0.12.2
plotly==5.15.0

# Jupyter
jupyter==1.0.0
ipykernel==6.25.0
ipywidgets==8.1.0

# Data Download
kaggle==1.5.16

# Model Persistence
joblib==1.3.2

# Utilities
tqdm==4.66.1
astropy==5.3.2
python-dotenv==1.0.0
