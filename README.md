# Data Science Portfolio
Tim Cody's Data Science Portfolio

## Deep Learning for Drug-Drug Interaction Prediction 
###### The importance of predicting drug-drug interactions (DDIs) cannot be overstated, given the risks they pose to patient safety and efficacy of medication management. DDIs are a common cause of adverse drug reactions (ADRs), particularly in elderly patients requiring polypharmacy. In fact, the prevalence of DDIs in polypharmacy patients ranges from 20-40%, highlighting the urgent need to develop effective strategies to mitigate these risks. Computational modeling has emerged as a promising approach to predicting potential DDIs, enabling clinicians and drug developers to identify potential interactions before they occur. Accurately predicting DDIs can lead to better clinical outcomes, reduced healthcare costs, and improved patient quality of life. Therefore, continued research and development in this area is critical to advancing the field of drug development and improving patient care.

###### This project aimed to develop a computational model to predict potential drug-drug interactions (DDIs) based solely on molecular structure. Accurately predicting DDIs can help mitigate the risks associated with polypharmacy and improve patient outcomes. Therefore, this study sought to build upon existing research and identify the most effective molecular representation for predicting DDIs.

###### To achieve this goal, several fingerprint representations were evaluated, including the ECFP4 fingerprint, Morgan fingerprint, and RDKit fingerprint. The performance of these fingerprints was compared based on their ability to accurately predict DDIs in a large database of drug pairs. The RDKit fingerprint was found to be the most effective at retaining the most information and achieving the best performance on the test set.

###### The final model developed in this study achieved a training accuracy of over 90%, which is on par with existing methods available in the literature. However, further improvements are possible by making changes to the drug representation or the structure of the network. Despite achieving high overall accuracy, the model struggled with some classes of DDIs, highlighting the need for further research to improve accuracy in these areas.

###### In summary, this project contributes to the development of effective strategies for mitigating the risks associated with DDIs. By accurately predicting potential interactions, clinicians and drug developers can improve patient outcomes, reduce healthcare costs, and enhance the quality of life for patients. Moreover, this study highlights the importance of selecting the appropriate molecular representation for predicting DDIs and provides insights for future research in this area.
<p align="center">
  <img src="https://github.com/Tcody6/tcody6.github.io/blob/main/img2DDI.png"/>
</p>
![](https://github.com/Tcody6/tcody6.github.io/blob/main/img2DDI.png)


## NFL Big Data Bowl 2023: Expected Protection Time
###### For the 2023 season the theme of the NFL's annual analytics competition was evaluating offensive and defensive linemen. This project aims to develop a new statistic, called Estimated Pass Time (EPT), for evaluating the performance of offensive and defensive lines in American football. The EPT metric is created using a variant of the Cox proportional hazards model, a widely used regression model in the medical field to study patient survival. In this project, the model is adapted to predict the time until the defense is able to end a pass play by sacking, hurrying, or forcing the quarterback to run. The gradient boosted Cox proportional hazards model is used to predict EPT, allowing for interactions between predictor variables, such as down and distance. The traditional pressure rate metric used in the NFL is limited, as it does not account for how long the offensive line maintained a clean pocket or other factors that can affect performance. 
###### Data preperation for this project was very involved. Data provided by the NFL was in the form of raw player tracking data that had to be transformed until usable data for input in a modle. Ultimatley this data was used to train a variation on a Cox Proportional Hazard model that predicts whether a pass will be unpressured (0) or result in a sack or pressure (1), as well as the amount of time before the event occurs. The team and player performance were modeled separately, with features such as down, distance, time remaining, score, number of rushers, number of blockers, play action, and formation included. For team performance, two models were trained for every team in the league's offense and defense, while for player performance, a model was created for every single team. The modeling approach involved a CPH model, with parameters tuned to optimize performance. A minimum of 30 pass rush plays were required for a player to be included in the analysis. This methodology was limited to evaluating defenders as offensive linemen do not rotate regularly in the NFL.

<p align="center">
  <img src="https://github.com/Tcody6/tcody6.github.io/blob/main/TeamEPT.png"/>
</p>
<p align="center">
  <img src="https://github.com/Tcody6/tcody6.github.io/blob/main/PlayerEPT.png"/>
</p>

## Best Buy Sales Forecasting
###### During the Best Buy MSA Project Week, I was part of a team that worked on forecasting slow-selling SKUs using time series analysis and machine learning techniques. Our main goal was to create a final dataset for model training by researching and sourcing external data for reuse and inclusion in the model. We also identified trends and seasonality patterns in the data to improve the model accuracy.

###### To achieve our objective, we tested multiple models and ultimately selected XGBoost due to its superior performance in both accuracy and computational speed. The project required a combination of technical and analytical skills, including data cleaning, exploratory data analysis, feature engineering, and model selection. By using XGBoost, we were able to generate accurate forecasts that helped Best Buy optimize their inventory and improve their bottom line. 
<p align="center">
  <img src="https://github.com/Tcody6/tcody6.github.io/blob/main/FI.jpg"/>
</p>
<p align="center">
  <img src="https://github.com/Tcody6/tcody6.github.io/blob/main/Trends.png"/>
</p>


## College Basketball Transfer Portal Network Analysis
###### The project focuses on analyzing the patterns and dynamics of player movements within the college basketball transfer portal using network analysis techniques. The authors aim to visualize the transfer network to identify the connections between different schools and conferences. The significance of the project lies in its potential to provide a better understanding of the transfer portal and its impact on college basketball, allowing for coaches to better plan for their future teams and target players on other teams.

###### The project involves extracting data from College Basketball Reference and creating links between players as they move between teams. By constructing graphs from the player tracking data, the authors can represent player interactions and movements as a network, where nodes represent players and edges represent connections between them. The visualization of the transfer network provides a dynamic representation of the movement of players over time, allowing for the identification of patterns and trends in player movement. The authors also plan to apply machine learning techniques to perform link prediction to predict future player movements based on the network's current state and other factors.

###### The project's analysis of the transfer network and factors influencing transfer decisions led to some important results. It was discovered that a small number of highly connected players had a significant impact on the network's connectivity and the decisions of other players. Additionally, the transfer networks are becoming increasingly connected over time, indicating that players' transfer behavior is becoming more interconnected and potentially more influenced by the decisions of others. The project's prediction model for transfers was also found to be highly accurate, with advanced statistics from the previous year being the most important feature in predicting transfers, followed by year in school and recruiting ranking. These results provide valuable insights for college basketball coaches and administrators in understanding the transfer portal's impact on the sport.

<p align="center">
  <img src="https://github.com/Tcody6/tcody6.github.io/blob/main/Results.png"/>
</p>
