# studying-fire-propagation-in-the-Brazilian-Amazon
 This study introduced an approach for wildfire risk prediction in the Brazilian Amazon, con
centrating in particular on the state of Pará, as a case study. By combining satellite-based
 vegetation indices, weather data, and indicators of human activity, we built a comprehensive
 spatiotemporal dataset covering a three-year period from 2022 to 2024. The modeling pro
cess compared multiple techniques, including ensemble tree-based models (Random Forest,
 LightGBM, XGBoost) and a spatiotemporal deep learning method (ConvLSTM), across two
 scenarios: one incorporating historical fire features and one excluding them.
 The findings show that both XGBoost and ConvLSTM achieved strong predictive perfor
mance, with ConvLSTM demonstrating strong pattern recognition in the absence of manually
 engineered historical features. However, XGBoost proved consistent across scenarios and was
 ultimately chosen for operational deployment due to its faster inference time and seamless in
tegration with spatial mapping tools.
 A significant insight from this research is that historical fire patterns had only a minor
 effect on model accuracy. Instead, variables reflecting real-time environmental stress, partic
ularly NDVI, temperature, and humidity, played a much larger role in predicting fire risk.
 This was additionally confirmed through feature importance analysis, which emphasized the
 importance of current, dynamic conditions over more static predictors like past fire occurrence
 or land cover types.
 Using the calibrated probabilities of the XGBoost model, we produced weekly fire risk
 maps for 2024 that classify areas according to their relative risk levels. These maps help iden
tify hotspots with a higher likelihood of fire occurrence for a given week. We included summary
 tables highlighting high-risk municipalities and point-based predictions in order to support the
 visualizations. This output provides useful insights for fire management agencies and environ
mental decision-makers.
 Overall, this work adds to the growing body of research on data-informed environmental
 forecasting, and provides a foundation for adaptable and scalable fire warning systems in the
 Amazon. This proposed modeling approach can be extended to other Amazonian regions or
 extended across time, contributing to long-term strategies for proactive fire prevention. By
 combining geospatial information with predictive modeling, this research demonstrates how
 data-driven methods can offer practical support in safeguarding vulnerable ecosystems like the
 Amazon
