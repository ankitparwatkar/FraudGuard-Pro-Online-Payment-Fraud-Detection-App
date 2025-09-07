# FraudGuard Pro - Online Payment Fraud Detection App

![FraudGuard Pro](https://img.shields.io/badge/FraudGuard-Pro-brightgreen) ![Python](https://img.shields.io/badge/Python-3.8%2B-blue) ![Streamlit](https://img.shields.io/badge/Streamlit-1.22.0-red) ![Machine Learning](https://img.shields.io/badge/Machine-Learning-orange) ![License](https://img.shields.io/badge/License-MIT-yellow)

FraudGuard Pro is an advanced AI-powered web application designed to detect fraudulent transactions in real-time using multiple machine learning models. This application provides financial institutions and payment processors with a powerful tool to identify and prevent fraudulent activities.

![FraudGuard Pro Interface](https://via.placeholder.com/800x400?text=FraudGuard+Pro+Interface+Screenshot)

## 🚀 Features

- **Multiple ML Models**: Choose between 5 different machine learning algorithms
- **Real-time Analysis**: Instant fraud detection with visual feedback
- **Comprehensive Dashboard**: Detailed transaction metrics and insights
- **Beautiful UI**: Modern gradient design with interactive elements
- **Performance Metrics**: Compare model accuracy and performance
- **Security Insights**: Get AI-powered security recommendations
- **Responsive Design**: Works seamlessly on desktop and mobile devices

## 🛡️ Supported Models

1. **Decision Tree** - 97.25% Accuracy
2. **K-Nearest Neighbors** - 97.03% Accuracy  
3. **Logistic Regression** - 94.37% Accuracy
4. **Naive Bayes** - 88.97% Accuracy
5. **Random Forest** - 97.77% Accuracy (Best Performance)

## 📋 Prerequisites

- Python 3.8+
- pip (Python package manager)

## 🛠️ Installation

1. Clone the repository:
```bash
git clone https://github.com/ankitparwatkar/FraudGuard-Pro-Online-Payment-Fraud-Detection-App.git
cd FraudGuard-Pro-Online-Payment-Fraud-Detection-App
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Place your trained models in the root directory (ensure these files are present):
- decision_tree_model.pkl
- KNeighbors_model.pkl  
- logistic_regression_model.pkl
- NaiveBayes_model.pkl
- random_forest_model.pkl

4. Run the application:
```bash
streamlit run main_app.py
```

5. Open your web browser and navigate to the local URL shown in the terminal (typically http://localhost:8501)

## 📊 Usage

1. **Select Model**: Choose your preferred ML model from the sidebar control panel
2. **Enter Transaction Details**:
   - Transaction type (CASH_OUT, PAYMENT, CASH_IN, TRANSFER, DEBIT)
   - Transaction amount
   - Sender's old and new balance
3. **Analyze**: Click "ANALYZE TRANSACTION" to get real-time fraud detection
4. **Review Results**: View detailed analysis and security recommendations

## 🏗️ Project Structure

```
FraudGuard-Pro-Online-Payment-Fraud-Detection-App/
│
├── main_app.py              # Main Streamlit application
├── requirements.txt         # Python dependencies
├── README.md               # Project documentation
├── decision_tree_model.pkl # Pre-trained Decision Tree model
├── KNeighbors_model.pkl    # Pre-trained KNN model
├── logistic_regression_model.pkl # Pre-trained Logistic Regression model
├── NaiveBayes_model.pkl    # Pre-trained Naive Bayes model
└── random_forest_model.pkl # Pre-trained Random Forest model
```

## 🎨 Interface Overview

The application features a modern dual-tone design:
- **Navy Blue** main section for content
- **Purple Gradient** sidebar for controls
- Animated results with color-coded alerts (Green for safe, Red for fraud)
- Interactive charts and metrics using Plotly
- Responsive card-based layout
- Social media integration in footer

## 🔧 Technical Details

- **Frontend**: Streamlit framework with custom CSS styling
- **Backend**: Python with Scikit-learn for machine learning
- **Visualization**: Plotly for interactive charts and graphs
- **Animation**: Lottie animations for enhanced user experience
- **Performance**: Optimized for real-time analysis with < 50ms response time

## 📈 Performance Metrics

- < 50ms analysis time per transaction
- Up to 97.77% detection accuracy (Random Forest)
- Real-time processing capabilities
- Low false positive rate
- Support for multiple transaction types

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Developer

**Ankit Parwatkar**
- GitHub: [@ankitparwatkar](https://github.com/ankitparwatkar)
- LinkedIn: [ankitparwatkar](https://linkedin.com/in/ankitparwatkar)
- Medium: [@ankitparwatkar35](https://medium.com/@ankitparwatkar35)
- Twitter: [@ankitparwatkar](https://twitter.com/ankitparwatkar)

## ⚠️ Disclaimer

This system uses machine learning to detect potential fraud patterns. Always verify suspicious transactions through official channels. The predictions should be used as a supplementary tool rather than the sole basis for decision-making.

## 🔮 Future Enhancements

- Integration with real payment gateways
- Additional machine learning models
- Historical transaction analysis
- User authentication and session management
- Advanced reporting and analytics
- API endpoints for third-party integration

---

⭐ If you find this project helpful, don't forget to give it a star on GitHub!
