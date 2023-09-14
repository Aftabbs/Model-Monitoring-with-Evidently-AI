# Model Monitoring with Evidently AI
![image](https://github.com/Aftabbs/Model-Monitoring-with-Evidently-AI/assets/112916888/6d71692e-f2ae-4fcb-a9ba-cdc4b416c802)


## Overview
This repository showcases a model monitoring project using Evidently AI, an open-source Python library. The project focuses on evaluating, testing, and monitoring data and machine learning models. It works with tabular data and enables data scientists and ML engineers to gain insights into model performance and data drift over time.

## Table of Contents
- [Introduction](#introduction)
- [Libraries Used](#libraries-used)
- [Why Evidently AI](#why-evidently-ai)
- [Why Model Monitoring](#why-model-monitoring)
- [Use Cases](#use-cases)
- [Project Details](#project-details)
- [Key Visualizations](#key-visualizations)
- [Enhancements](#enhancements)
- [Conclusion](#conclusion)

## Introduction
In the field of data science and machine learning, monitoring models in production is essential. The Evidently AI library allows us to assess model performance, identify data drift, and ensure that our models continue to deliver accurate predictions over time. This repository demonstrates how to use Evidently AI for model monitoring and provides insights into why it's a critical component of the ML lifecycle.

## Libraries Used
- **Pandas:** For data manipulation and analysis.
- **Numpy:** For numerical operations.
- **Scikit-Learn:** For machine learning tasks, including building the regression model.
- **Evidently AI:** For model monitoring and generating detailed reports.

## Why Evidently AI
Evidently AI is a powerful tool for data scientists and ML engineers for several reasons:
- **Holistic Model Monitoring:** Evidently AI provides a comprehensive solution for monitoring both model performance and data drift.
- **Integration:** It seamlessly integrates with existing data science workflows and can be used in production environments.
- **Open-Source:** Being open-source, it offers flexibility and customization options for specific use cases.

## Why Model Monitoring
Model monitoring is necessary for several reasons:
- **Model Drift:** Over time, model performance can deteriorate due to changes in the data distribution. Monitoring helps identify and mitigate this issue.
- **Business Impact:** Accurate models are critical for decision-making and business success. Monitoring ensures models remain reliable.
- **Compliance:** In regulated industries, monitoring is essential to meet compliance requirements and maintain data and model integrity.

## Use Cases
Model monitoring with Evidently AI has wide-ranging industry applications, including:
- **Finance:** Monitoring financial models for fraud detection, risk assessment, and investment predictions.
- **Healthcare:** Ensuring the accuracy of medical diagnosis and treatment recommendation models.
- **E-commerce:** Tracking sales and demand forecasting models to optimize inventory and pricing.
- **Manufacturing:** Monitoring equipment failure prediction models for preventive maintenance.

## Project Details
- **Dataset:** Bicycle Sales demand data with columns [instant, season, yr, mnth, hr, holiday, weekday, workingday, weathersit, temp, atemp, hum, windspeed, casual, registered, cnt].
- **Target:** 'cnt'
- **Prediction:** 'prediction'
- **Model:** Random Forest Regressor

## Key Visualizations
- **Predicted vs. Actual:** Visualizing the predicted vs. actual values to assess model accuracy.
- **Error Bias Table:** Identifying bias in model errors for different data segments.
- **Underestimation Percentage:** Understanding the percentage of cases where the model underestimates the target.
- **Overestimation Percentage:** Understanding the percentage of cases where the model overestimates the target.
- **Data Drift Analysis:** Monitoring data drift in all columns over time to ensure data quality.
![image](https://github.com/Aftabbs/Model-Monitoring-with-Evidently-AI/assets/112916888/ee4014d6-3e2f-4fd1-a353-18dd18534468)
![image](https://github.com/Aftabbs/Model-Monitoring-with-Evidently-AI/assets/112916888/c37bb044-39f0-40c8-93e8-72f3c06898f8)
![image](https://github.com/Aftabbs/Model-Monitoring-with-Evidently-AI/assets/112916888/dd8eaeb3-92fb-4ce7-9f4a-6a33eda6be86)
![image](https://github.com/Aftabbs/Model-Monitoring-with-Evidently-AI/assets/112916888/14573467-0485-4cd6-8b36-25c8be237637)
![image](https://github.com/Aftabbs/Model-Monitoring-with-Evidently-AI/assets/112916888/bf63b6a9-856d-4cc1-8faa-fa7327a5ac45)
![image](https://github.com/Aftabbs/Model-Monitoring-with-Evidently-AI/assets/112916888/44525868-eaf5-4895-8dbf-556cecc7ba05)
![image](https://github.com/Aftabbs/Model-Monitoring-with-Evidently-AI/assets/112916888/14fe253c-2621-458b-a8a2-3be19cb1b8a4)

## Enhancements
To further enhance this project, consider:
- **Real-time Monitoring:** Implement real-time model monitoring to detect issues promptly.
- **Alerting System:** Set up automated alerts for significant deviations in model performance.
- **Integration with Deployment Pipelines:** Integrate Evidently AI into your deployment pipelines for seamless model monitoring in production.

## Conclusion
Model monitoring with Evidently AI is a critical component of ensuring that machine learning models remain accurate and reliable in production. This repository demonstrates how to use Evidently AI for monitoring a regression model and provides valuable insights into the importance of model monitoring in various industries.

Feel free to adapt and customize this `Readme.md` file with your specific project details and use cases. Upload it to your GitHub repository to share your project with others and promote best practices in model monitoring.
