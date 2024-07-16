# INTEGRATING-GRAPH-CONVOLUTIONAL-NETWORKS-AND-ARIMA-FOR-URBAN-RAIL-TRANSIT-PASSENGER-FLOW-FORECASTING

## **Objectives**

The primary objectives of this project are:

-To apply the hybrid GCN-ARIMA model to a dataset containing passenger flow data recorded at 10-minute, 15-minute, and 30-minute intervals for both in-flow and out-flow at each station.

-To evaluate the model's performance using key metrics such as Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and Weighted Mean Absolute Percentage Error (WMAPE).

-To improve the accuracy and reliability of passenger flow predictions, thereby enabling more effective resource allocation and scheduling in urban rail transit systems.

-To validate the model's robustness and practical applicability across different operational contexts.

## **Proposed Work**

## **1)Data Collection**
The dataset includes passenger flow data recorded at 10-minute, 15-minute, and 30-minute intervals for both in-flow and out-flow at each station.
Graphical data includes the urban rail network structure, with nodes representing stations and edges representing direct connections between stations.

## **2)Preprocessing**
Time series analysis will be applied to decompose the data into trend, seasonality, and residual components.
A graph representation of the rail network will be constructed to facilitate GCN modeling.

## **3)Model Development**
-GCN Implementation: Graph Convolutional Networks will be implemented to capture spatial dependencies. Multiple GCN layers will process the graph data, extracting features that reflect the inter-station relationships.

-ARIMA Integration: The residuals from the GCN model will be fed into an ARIMA model to incorporate temporal dynamics. Parameter selection for ARIMA (e.g., autoregressive order, differencing, moving average order) will be optimized based on the decomposed time series components.

-Hybridization: Both sequential and parallel integration strategies will be explored where GCN and ARIMA models inform each other iteratively or simultaneously to achieve the best prediction performance.

## **4)Training and Testing Split**
The dataset is divided into training and testing sets, with the majority of data used for training the models and a smaller portion for testing to evaluate performance.

## **5)Metrics**

Performance evaluation will be based on standard metrics such as:

-Mean Absolute Error (MAE)

-Root Mean Squared Error (RMSE)

-Coefficient of Determination (R2)

-Weighted Mean Absolute Percentage Error (WMAPE)

![image](https://github.com/user-attachments/assets/0df28d05-47d4-4c10-ab74-cb9bac3e2a47)

