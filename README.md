# Algeria DataCup 3.0: Unilever Delivery Optimization

## Introduction
This project proposes a solution for the bonus challenge presented at the Algeria DataCup 3.0 (ADC 3.0). The challenge involves optimizing the delivery process in the Algiers area for Unilever, a multinational fast-moving consumer goods company.

## Problem Definition
Unilever's challenge at ADC 3.0 is to predict the optimal number of vendors and trucks needed for efficient distribution in the Algiers area. Historical sales data is provided, enabling a prediction-based approach to address the problem.

## Proposed Solution
The proposed solution involves two main parts:

1. **Data Preparation and Feature Engineering:** The provided dataset undergoes extensive preprocessing and feature engineering. Data is organized based on customer locations and products used over time during specific days of the week.

2. **Optimization Algorithm:** The project utilizes a Genetic Algorithm-based P-median Optimization (GBPMO) approach, adapted from IoT systems, to optimize delivery planning. This algorithm minimizes the distance between delivery locations and the company base while adhering to constraints such as vendor capacities.


## Files
- `data_preprocessing.py`: Python script for data preprocessing and feature engineering.
- `optimization_algorithm.py`: Python script implementing the GBPMO optimization algorithm.
- `README.md`: This file providing an overview of the project.

## Future Perspectives
The project offers potential avenues for future improvement and expansion:
- Integration of neural network models for efficient planning without relying on optimizers.
- Development of predictive models for salesman assignment and customer preferences.
- Further optimization and parameter tuning for improved accuracy and efficiency.

## Conclusion
The Unilever Delivery Optimization project presents a novel approach to address distribution challenges using optimization algorithms and data-driven insights. While the current implementation shows promising results, future enhancements and integrations can unlock even greater efficiency and accuracy in delivery planning.

## Contacts
Feel free to reach out to the contributors for further information:
- **Said Guerazem**
  - Email: said.guerazem@g.enp.edu.dz
  - LinkedIn: [linkedin.com/in/said-guerazem](https://www.linkedin.com/in/said-guerazem)
  
- **Omar Mameche**
  - Email: omar.mameche@g.enp.edu.dz
  - LinkedIn: [linkedin.com/in/omar-mameche-68bba9243](https://www.linkedin.com/in/omar-mameche-68bba9243)
  
- **Abedou Abdelhadi**
  - Email: abdelhadi.abedou@g.enp.edu.dz
  - LinkedIn: [linkedin.com/in/abedou-abdelhadi-5b72b5235](https://www.linkedin.com/in/abedou-abdelhadi-5b72b5235)
  
- **Abdelbaki GUIR**
  - Email: abdelbaki.guir@g.enp.edu.dz
  - LinkedIn: [linkedin.com/in/abdelbakiguir](https://www.linkedin.com/in/abdelbakiguir)
