# Collaborative Filtering - SVD
Collaborative Filtering: This approach, build a model from past behaviors, comparing items or users trough ratings, and in this case the SVD (Singular Value Decomposition) technique can extract k features that can be used to find similar users/items. The function returns: the predictions, the rmse (root mean square error), the U matrix (users relation to the features), the Sigma matrix (features matrix)and the V matrix (items relation to the features).

* Xdata = Dataset Attributes. A matrix with users ratings about a set of items.

* mean_centering = "none", "row", "column", "global". If "none" is selected then no centering is made, if "row" is selected then a row mean centering is performed,  if "column" is selected then a column mean centering is performed and if "global" is selected then a global centering (matrix mean) is performed. The default value is "none".

* k = Total number of features to be extracted. The default value is 2.

* user_in_columns = Boolean that indicates if the user is in the column (user_in_column = True) then a user-user similarity is made, if (user_in_column = False) then an item-item similarity is performed instead. The default value is True.

* graph = Boolean that indicates if the first 2 features of the users and items will be displayed (graph = True) or not (graph = False). The default value is True.
