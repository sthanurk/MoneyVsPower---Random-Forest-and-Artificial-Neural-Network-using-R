# Can Money Buy Power?
Predicting if Money can buy Political Power
An analysis on Elections Data in R

Methods used : Random Forest, Artificial Neural Network

__Random Forest Best Model:__ 
Number of trees (ntree) = __70__  
Number of variables (mtry) = __5__  
Out-of-Bag (OOB) error rate = __5.38%__  

Accuracy of Random Forest Model in Predicting the election results from various factors = __90.65%__

The main factors influencing the election results in the order of influence : 
* Opp_fund (Operation Funds)
* facebook (Facebook Social Media Campaign)
* other_pol_cmte_contrib (Contributions from Other Political Committees)
* coh_cop (Cash at end of campaign)
* ttl_disb (Total Disbursements of funds)

__Artificial Neural Network:__
Number of input nodes in the ANN = __39__  
Number of weights in the ANN =  __206__

Best Model is Random Forest in comparison to the Neural Network model.
__Area under the Receiver Operating Characteristics (ROC) curve (AUC):__ 
* Random Forest Model = 98%
* Artificial Neural network Model = 95.4%