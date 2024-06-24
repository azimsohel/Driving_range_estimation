The adoption of electric vehicles (EVs) has been accelerating rapidly, establishing them as a 
sustainable mode of transportation. However, one of the critical challenges for wider EV acceptance 
is the need for precise driving range estimation. This enhances driver confidence and addresses 
common concerns such as range anxiety. Traditional range estimation methods, often based on 
average energy consumption, need more accuracy for effective trip planning. This research 
emphasizes the integration of complex data sets, encompassing vehicle characteristics, driver 
behaviour, and real-time environmental factors, to refine the accuracy of range estimations. 
This study uses a dataset from a crowdsource platform named SpritMonitor to explore the efficacy 
of various machine learning models in predicting EV driving ranges. The research critically 
compares Linear Regression, Random Forest Regression, and Deep Multilayer Perceptron (Deep 
MLP) models, evaluating their performance using metrics such as Mean Absolute Error (MAE), 
Mean Absolute Percentage Error (MAPE), and R-squared (R²). 
Innovatively, this study incorporates Federated Learning (FL) to provide privacy-preserving 
estimations of driving ranges. FL’s distinctive approach not only enhances data security but also 
maintains the accuracy of predictions. Utilizing the Federated Averaging (FedAvg) method, the 
research demonstrates FL's viability by applying it across varying test-set sizes and analyzing the 
resultant error metrics. Additionally, it explores the impacts of distributing datasets equally and 
unequally among clients, and it tests various configurations of training epochs and activation 
functions, with a particular focus on comparing the effects of ReLU and ELU. Furthermore, the 
introduction of FedProx addresses challenges with non-IID data, significantly enhancing stability 
and convergence in diverse client data environments. These explorations underscore the potential 
of FL as a robust methodology for future advancements in EV range estimation, highlighting its 
adaptability and effectiveness in improving prediction accuracy while safeguarding data privacy. 
