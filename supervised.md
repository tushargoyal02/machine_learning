# Supervised machine learning

*   Classification
*   Regression

Well organised data is neccessary in Supervised Learning.

* Features are characterstic 
* Label are the target value or the actual value.
##  Classification
*   Is used to classify different items 
    
    *   KNN 
    *   Decision Tree
    *   Random Forest   
    *   

            pip3 install scikit-learn

### Decision Tree
*   ID3 & cart are the algorithm which run behind the Decsion Tree.



        from sklearn.tree import DecisionTreeClassifier
*   Graph wizard - This can be used what Decision Tree is using as priority to give answer

    *   Example - House Price, Cancer, Flower Type prediction

##   *  Dividing data into percentage
    
    from sklearn.model_selection import train_test_split

*   Dividing data in percentage. 
    * train_data, test_data, label_train, label_test =   train_test_split(features, label, test_size=0.2)



