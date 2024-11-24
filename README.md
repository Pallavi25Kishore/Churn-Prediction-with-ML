
# :chart:ChurnGuard - A Solution for Customer Churn Prediction and Mitigation

## :books:About
ChurnGuard is a web application designed to predict customer churn and provide actionable insights to retain at-risk customers. By leveraging advanced machine learning and generative AI, ChurnGuard empowers businesses to reduce churn and strengthen customer relationships.

<div align="center">
  <h3>ChurnGuard Dashboard</h3>
  <img src="churn-prediction/public/finalgif.gif" alt="ChurnGuarddashboard gif" width="600px" />
</div>

## :video_camera:Deployed App Demo on youtube
<div align="center">
  <a href="https://youtu.be/NQAymmtNgfo">
    <img src="https://img.youtube.com/vi/NQAymmtNgfo/0.jpg"" alt="Watch the demo video" width="800px"/>
  </a>
</div>

## :rocket:Technologies
### Front-End
![Static Badge](https://img.shields.io/badge/javascript-yellow?style=for-the-badge)
![Static Badge](https://img.shields.io/badge/React-yellow?style=for-the-badge)
![Static Badge](https://img.shields.io/badge/HTML%2FCSS-yellow?style=for-the-badge)
![Static Badge](https://img.shields.io/badge/Tailwind-yellow?style=for-the-badge)
![Static Badge](https://img.shields.io/badge/Recharts-yellow?style=for-the-badge)
![Static Badge](https://img.shields.io/badge/reactd3speedometer-yellow?style=for-the-badge)

### Back-End 
![Static Badge](https://img.shields.io/badge/python-yellow?style=for-the-badge)
![Static Badge](https://img.shields.io/badge/flask-yellow?style=for-the-badge)

### Other Tools/ Machine Learning + Generative AI 
![Static Badge](https://img.shields.io/badge/kaggle-yellow?style=for-the-badge)
![Static Badge](https://img.shields.io/badge/pandas-yellow?style=for-the-badge)
![Static Badge](https://img.shields.io/badge/numpy-yellow?style=for-the-badge)
![Static Badge](https://img.shields.io/badge/scipy-yellow?style=for-the-badge)
![Static Badge](https://img.shields.io/badge/seaborn-yellow?style=for-the-badge)
![Static Badge](https://img.shields.io/badge/groq-yellow?style=for-the-badge)
![Static Badge](https://img.shields.io/badge/google%20colab-yellow?style=for-the-badge)
![Static Badge](https://img.shields.io/badge/gemma2-yellow?style=for-the-badge)
![Static Badge](https://img.shields.io/badge/scikit%20learn-yellow?style=for-the-badge)

### Deployment
![Static Badge](https://img.shields.io/badge/vercel-yellow?style=for-the-badge)
![Static Badge](https://img.shields.io/badge/render-yellow?style=for-the-badge)

## :gear: Features

- [X] **Customer Churn Prediction**: Predict churn probabilities using ML models.
- [X] **Actionable Insights**: Detailed explanations of why a customer is at risk of churning, powered by Google’s Gemma2.
- [X]  **Personalized Retention Strategies**: Automatically generate customer-specific emails to incentivize loyalty.
- [X]  **Dynamic Dashboards**: Interactive visualizations including:
        - **Speedometer**: Displays average churn probability.
        - **Model Predictions**: Bar chart of churn probabilities from individual ML models.
        -**Customer Ranking**: Bar chart showing percentile rank among peers.

## :rocket: Machine Learning Workflow

1. **Dataset**:  
   - Bank customer dataset from Kaggle.

2. **Data Splitting**:  
   - The dataset was split into 80/20 ratio (80% for training and 20% for testing)

3. **Feature Engineering**:  
   - Performed feature selection, transformation, and creation to enhance the dataset.  
   - Addressed class imbalance using SMOTE to oversample the minority class.

4. **Models Trained**:  
   - XGBoost  
   - k-Nearest Neighbors  
   - Gradient Boosting  
   - ExtraTrees  
   - AdaBoost  

5. **Ensembling Techniques**:  
   - Implemented **voting classifiers**, **stacking**, and **bagging** to combine the strengths of multiple models and improve predictive performance.  

6. **Performance Metrics**:  
   - **Accuracy**: 0.851500  
   - **Recall**: 0.62
   - In the context of ChurnGuard, recall is a critical metric because it measures the model's ability to correctly identify customers who are at risk of churning and the cost of false negatives is much higher than the cost of false positives.
   - 
## :computer: Application Architecture

### Frontend:
- Built with **React** for an intuitive and dynamic user experience.
- Deployed on **Vercel** for scalability and reliability.

### Backend:
- Powered by **Flask**, which handles API services and integrates with AI tools.
- Deployed on **Render** for seamless performance.

### Integration with Generative AI:
- Google’s **Gemma2** generates:
  - Explanations for churn predictions.
  - Personalized emails to incentivize at-risk customers.

## :sparkles:Getting Started
### Prerequisites
![NPM](https://img.shields.io/badge/NPM-%23000000.svg?style=for-the-badge&logo=npm&logoColor=white)
```sh
npm install
```

### Installation
1. Clone the repo.
```sh
  git clone https://github.com/Pallavi25Kishore/Rhythm.git
```

2. Install NPM packages.
```sh
  npm install
```

3. Make a copy of the .exampleenv file and rename it to .env. Enter the following in the .env file.
```sh
PORT = PORT
DB_HOST = "host name"
DB_USER = "username"
DB_NAME = "name of database"
DB_PASSWORD = "password"
DB_PORT = DB PORT
```

4. Run in dev environment.
```sh
  npm run server-dev
  npm run react-dev
```


