# Yandex-ML-handbook-tasks
Solving problems from the Yandex ML Handbook

## 🚀 Quick Start with Docker

This repository is set up for data science work with Jupyter notebooks using Docker.

### Prerequisites
- Docker
- Docker Compose

### Setup and Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/HoshiBatista/Yandex-ML-handbook-tasks.git
   cd Yandex-ML-handbook-tasks
   ```

2. **Start Jupyter Lab with Docker Compose:**
   ```bash
   docker-compose up --build
   ```

3. **Access Jupyter Lab:**
   Open your browser and go to `http://localhost:8888`

4. **Stop the environment:**
   ```bash
   docker-compose down
   ```

### Alternative Docker Commands

**Build the image manually:**
```bash
docker build -t yandex-ml-tasks .
```

**Run the container:**
```bash
docker run -p 8888:8888 -v $(pwd):/app yandex-ml-tasks
```

## 📦 Included Packages

The environment includes essential data science libraries:
- **Jupyter**: Lab and Notebook environments
- **Data Analysis**: pandas, numpy, scipy
- **Machine Learning**: scikit-learn, xgboost, lightgbm
- **Visualization**: matplotlib, seaborn, plotly
- **Statistics**: statsmodels
- **Utilities**: tqdm, joblib, requests

## 🛠 Local Development

If you prefer to work without Docker:

1. **Create a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Start Jupyter Lab:**
   ```bash
   jupyter lab
   ```
