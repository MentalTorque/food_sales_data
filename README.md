# Food Sales Data Analysis

Our client has tasked us with helping them determine the best ways to optimize sales in the existing locations as well what factors will allow them to establish future food stores with more robust sales outputs.

We were provided a dataset to analyze with the following characteristics in sales distribution:


<img src='Images/dist_outlet_sales.png' width=50%>



## Linear Regression Coefficient
<img src='Images/sales_lin_reg_coeffs.png' width=50%>




Top 10 most important features are:

<img src='Images/top_10_most_important_features.png' width=50%>
                                                     
                                                     
Comparing Itemn MRP to Outlet Sales shows...
<img src='Images/item_mrp_to_outlet_sales.png' width=50%>

                                              
Outlet Sale as a function of Grocery Store Type is...                                  
<img src='Images/outlet_type_grocery_store_to_outlet_sales.png' width=50%>


Item visibility with respect to generation of outlet sales looks like...
<img src='Images/item_visibility_to_outlet_sales.png' width=50%>


Item Weight as it imppacts outlet sales within the model is...
<img src='Images/item_weight_to_outlet_sales.png' width=50%>


Analyzing the permutation importances to see how they line up with the model's asserted most important features shows...
<img src='Images/reg_perm_importances.png' width=50%>


Using SHAP to conduct further analysis of the model, the barplot visual tells us...
<img src='Images/shap_summary_barplot.png' width=50%>

A bit more insightful than the barplot, the dots indicate a better idea of the distribution of feature effects within the model...
<img src='Images/shap_summary_plot.png' width=50%>


Checking the forceplot of the lowest sales , we see the weights of features as...
<img src='Images/shap_idx_low_sales_forceplot.png' width=50%>

Checking the forceplot of the highest sales , we see the weights of features as...
<img src='Images/shap_idx_high_sales_forceplot.png' width=50%>







