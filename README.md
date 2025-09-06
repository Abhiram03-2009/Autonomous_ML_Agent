# 🤖 Autonomous ML Agent

**An intelligent machine learning platform that automatically trains and optimizes models using LLM orchestration, providing real-world predictions with meaningful insights.**

## 🎯 Problem Being Solved

**Traditional ML Development Challenges:**
- ⏰ **Time-consuming**: Manual model selection and hyperparameter tuning takes days/weeks
- 🧠 **Expertise Required**: Need deep ML knowledge to choose optimal algorithms
- 🔄 **Repetitive Process**: Same workflow for every new dataset
- 📊 **Limited Exploration**: Usually test only 2-3 models due to time constraints
- 🎲 **Trial & Error**: No systematic approach to model optimization
- 📈 **Performance Uncertainty**: Hard to know if you've found the best solution

## 💡 The Solution

**Autonomous ML Agent Features:**
- 🚀 **Automated Pipeline**: End-to-end ML workflow in minutes, not days
- 🤖 **AI-Driven Strategy**: LLM generates optimal experiment plans
- 📊 **Multi-Model Testing**: Automatically tests 5+ algorithms with optimization
- 🎯 **Smart Hyperparameter Tuning**: Uses advanced optimization techniques
- 📈 **Real-time Monitoring**: Live progress tracking and performance updates
- 🏆 **Intelligent Selection**: Automatically finds the best performing model
- 📥 **Production Ready**: Generates deployable models and documentation
- 🧪 **Interactive Testing**: Built-in prediction interface for model validation

## 🚀 Quick Start

### Prerequisites
- Python 3.8 or higher
- pip package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Abhiram03-2009/Autonomous_ML_Agent.git
   cd Autonomous_ML_agent
   ```

2. **Create virtual environment**
   ```bash
   python -m venv venv
   
   # Windows
   venv\Scripts\activate
   
   # macOS/Linux
   source venv/bin/activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the web interface**
   ```bash
   streamlit run simple_demo.py --server.port 8502
   ```

5. **Open your browser**
   ```
   http://localhost:8502
   ```

## 🎮 How to Use

### 1. **Upload Your Dataset**
- Click "Browse files" and select a CSV file
- The system automatically detects features and target columns
- Preview your data before training

### 2. **Configure Training**
- Select your target column (what you want to predict)
- Choose feature columns (input variables)
- Set training parameters (test size, max experiments)

### 3. **Start Training**
- Click "🚀 Start Training" to begin the automated ML pipeline
- Watch real-time progress updates
- The system tests multiple algorithms automatically

### 4. **View Results**
- **Leaderboard**: See all tested models ranked by performance
- **Best Model**: View the top-performing algorithm
- **Insights**: Get automated analysis and recommendations
- **Download**: Export model code, results, and reports

### 5. **Test Your Model**
- **Manual Input**: Enter values manually for single predictions
- **Upload Test Data**: Batch predictions from CSV files
- **Sample Predictions**: Test with random samples from your dataset

## 📊 Supported Datasets

### 🚢 **Titanic Survival Prediction**
- **Features**: Age, Sex, Class, Fare, etc.
- **Target**: Survived (0/1)
- **Example**: "25-year-old female in first class had 89% survival probability"

### 🌸 **Iris Species Classification**
- **Features**: Sepal length, Petal length, Sepal width, Petal width
- **Target**: Species (Setosa, Versicolor, Virginica)
- **Example**: "Flower with 6.2cm sepal length is predicted as Virginica with 92% confidence"

### 🏠 **Housing Price Prediction**
- **Features**: Rooms, Age, Location, Crime rate, etc.
- **Target**: Price/Value
- **Example**: "House with 6 rooms in good location predicted at $450,000"

## 🏗️ Architecture

```
┌─────────────────┐    ┌──────────────────┐    ┌─────────────────┐
│   Web Interface │    │  LLM Orchestrator|    │  ML Pipeline    │
│   (Streamlit)   │◄──►│   (Strategy)     |◄──►│  (Execution)    │
└─────────────────┘    └──────────────────┘    └─────────────────┘
         │                       │                       │
         ▼                       ▼                       ▼
┌─────────────────┐    ┌──────────────────┐    ┌─────────────────┐
│  User Interface │    │  Experience DB   │    │  Model Training │
│  & Predictions  │    │  (Meta-learning) │    │  & Optimization │
└─────────────────┘    └──────────────────┘    └─────────────────┘
```

```
## 📁 Project Structure

autonomous-ml-agent/
├── autonomous_ml/           # Core ML agent package
│   ├── core.py             # Main orchestrator
│   ├── config.py           # Configuration settings
│   ├── models.py           # Model registry
│   ├── preprocessing.py    # Data preprocessing
│   ├── web_dashboard.py    # Streamlit dashboard
│   └── web_api.py          # FastAPI backend
├── examples/               # Sample datasets and notebooks
│   └── datasets/           # Example CSV files
├── simple_demo.py          # Main demo application
├── requirements.txt        # Python dependencies
├── pyproject.toml          # Project configuration
└── README.md              # This file
```

**Made by Abhiram Kaakarla**

*Transform your data into actionable insights with the power of autonomous machine learning!*

