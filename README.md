# Neural_Network_Charity_Analysis

* Target for the Model: "IS_SUCCESSFUL"
* Features for the Model: 'STATUS', 'IS_SUCCESSFUL', 'APPLICATION_TYPE_Other',
       'APPLICATION_TYPE_T10', 'APPLICATION_TYPE_T19', 'APPLICATION_TYPE_T3',
       'APPLICATION_TYPE_T4', 'APPLICATION_TYPE_T5', 'APPLICATION_TYPE_T6',
       'APPLICATION_TYPE_T7', 'APPLICATION_TYPE_T8',
       'AFFILIATION_CompanySponsored',
       'AFFILIATION_FamilyParentNationalRegionalOther',
       'AFFILIATION_Independent', 'CLASSIFICATION_C1000',
       'CLASSIFICATION_C1200', 'CLASSIFICATION_C2000', 'CLASSIFICATION_C2100',
       'CLASSIFICATION_C3000', 'CLASSIFICATION_Other',
       'USE_CASE_CommService_Healthcare_Other', 'USE_CASE_Preservation',
       'USE_CASE_ProductDev', 'ORGANIZATION_Association',
       'ORGANIZATION_CoOps_Corps', 'ORGANIZATION_Trust', 'INCOME_AMT_0',
       'INCOME_AMT_100000-499999', 'INCOME_AMT_1m_to_50m+',
       'INCOME_AMT_25000-99999', 'SPECIAL_CONSIDERATIONS_N',
       'SPECIAL_CONSIDERATIONS_Y'
* Features to be dropped:  'ASK_AMT,' 'EIN,' and 'NAME'
* How many layers in the model & why:  I chose 3 Hidden Layers and 1 Output layer to address the perceived complexity of predicting the output.  I also chose 8, 5, 5 neurons  respectively for my 3 hidden layers, and the activation function I chose for these was both the 'relu' and the 'tanh' over two different attempts to run the model.  For the output layer, I always chose 'sigmoid' because it was a yes-no kind of an answer for the target variable.
* Where you able to achieve the target performance:  No, the closest I got was 73% accuracy
*  What steps did I take to Optimize the model:  1. I tried to bin more values in categorical variables that had many categories with few counts.  2. I tried both the 'relu' and the 'tanh' activation functions.  3.  I tried dropping 'ASK_AMT' as an attempt to get rid of needless inputs. 
