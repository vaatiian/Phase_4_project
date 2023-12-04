 # DJIA Prediction System

## Project Overview

The DJIA Prediction System project aims to address the complexities of predicting the short-term movement of the Dow Jones Industrial Average (DJIA). By leveraging advanced machine learning techniques, the project seeks to provide valuable insights for investors and financial institutions, enabling them to make informed decisions about investment strategies and risk management.

## Collaborators

- Ian Vaati
- Sylvia Murithi
- Bushra Mohammed

## Project Submission Date

December 11th, 2023.

## Business Understanding

### Executive Summary

In the dynamic landscape of the stock market, accurately predicting the movement of the DJIA is crucial for effective decision-making. The project endeavors to surpass traditional forecasting methods by developing and deploying sophisticated machine learning models. These models aim to empower stakeholders with enhanced forecasting accuracy, risk mitigation strategies, decision support, and deeper market intelligence.

### Business Problem

The inherent volatility and unpredictability of financial markets pose significant challenges to existing forecasting methods. This project acknowledges these challenges and seeks to provide a more robust solution by employing advanced machine learning techniques. By doing so, the project aims to improve the accuracy and reliability of DJIA predictions.

### Business Objectives

1. **Forecasting Accuracy:** Develop precise models capable of predicting future trends in the DJIA, providing stakeholders with the ability to anticipate market movements with unprecedented precision.

2. **Risk Mitigation:** Provide insights into potential market risks and opportunities, allowing for the development of proactive risk management strategies for investors and financial institutions.

3. **Decision Support:** Equip decision-makers with actionable information derived from predictive models, empowering them to make informed investment decisions and optimize portfolio management.

4. **Market Intelligence:** Enhance market intelligence by identifying patterns, trends, and key indicators that contribute to a deeper understanding of market dynamics.

## Key Deliverables

The project aims to deliver the following key components:

1. **Predictive Models:** Develop and deploy machine learning models capable of forecasting future values of the DJIA. These models will undergo rigorous evaluation to ensure their accuracy and reliability.

2. **Visualizations and Reports:** Provide visually appealing and informative representations of market trends, predictions, and relevant indicators. These visualizations will serve as valuable tools for decision-makers.

3. **Documentation:** Create comprehensive documentation that outlines the methodologies, data sources, model selection rationale, and performance evaluation metrics. This documentation will ensure transparency and ease of understanding for stakeholders.

4. **Training and Support:** Offer training sessions and ongoing support to stakeholders on interpreting and utilizing predictive models effectively. This includes guidance on how to integrate model outputs into their decision-making processes.

## Success Criteria

The success of the project will be evaluated based on the following criteria:

1. **Accuracy:** The developed machine learning model must accurately predict the direction of DJIA movement for the specified time horizon.

2. **Outperformance:** The model should consistently outperform benchmark models, such as a simple moving average, in terms of accuracy.

3. **User-Friendly Interface:** The web application or API developed as part of the project should provide a user-friendly interface for obtaining DJIA predictions. Users should find it intuitive and easy to navigate.

By meeting these success criteria, the project aims to showcase the efficacy of machine learning in providing valuable insights into stock market movements.

## Methodology

### Research Questions

The project addresses the following research questions:

1. Can historical data from Dow Jones Industrial Average (DJIA) be used to predict future market trends accurately?

2. What key features or indicators contribute significantly to predicting stock market movements?

3. Which machine learning algorithms are best suited for predicting DJIA movement?

### Hypothesis

The project operates under the following hypotheses:

1. Historical trends and patterns in Dow Jones data can be leveraged to forecast future market trends with reasonable accuracy.

2. Technical indicators like moving averages, relative strength index (RSI), and MACD will be crucial features for predicting stock market trends.

3. Time series forecasting models like ARIMA, LSTM, and Prophet will outperform basic regression models in predicting stock market movements.

## Research Design

The project employs an analytical approach by applying various machine learning models to historical Dow Jones data. Emphasis is placed on time series analysis methodologies to capture the sequential nature of stock market data.

## Data Description

### Data Source

The project utilizes data collected from the investing.com website, covering historical data for the Dow Jones Industrial Average (DJIA) from 01/03/2000 to 11/24/2023. The dataset includes attributes such as Date, Close, Open, High, Low, Volume, and Change %.

## Summary of Model Training

The project involves the training and evaluation of several machine learning models, including a Random Forest Classifier, an LSTM (Long Short-Term Memory) neural network, and the Prophet time series forecasting model. The models are assessed based on accuracy, mean squared error (MSE), and other relevant metrics.

### Random Forest Classifier

- **Best Hyperparameters:** {'learning_rate': 0.01, 'max_depth': 3, 'n_estimators': 200}
- **Accuracy:**

 0.5426
- **Classification Report:** Precision, recall, and f1-score for binary classification.

### LSTM Model

- **Epochs:** 50
- **Mean Squared Error (MSE):** 904,846,274.03

### Prophet Model

- **Mean Squared Error (MSE):** 884,367,575.03

Considering the results, the Prophet Model exhibits the lowest MSE among the presented models, suggesting its potential as the most suitable choice for predicting the short-term movement of the Dow Jones Industrial Average.

## Investor Recommendations

The project recommends that investors consider the predictions provided by the Prophet Model as a valuable tool in their decision-making processes. While no predictive model is infallible, the consistently low MSE of the Prophet Model indicates its relative accuracy in forecasting DJIA movements.

Investors are advised to use these predictions in conjunction with other fundamental and technical analyses to make well-informed investment decisions. Additionally, continuous monitoring and adaptation of strategies based on real-time market conditions are essential.

By incorporating machine learning predictions into their investment strategies, investors can gain a more nuanced understanding of potential market trends and, consequently, enhance their overall portfolio management.
