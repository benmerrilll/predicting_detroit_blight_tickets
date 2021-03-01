# predicting_detroit_blight_tickets

This project is based on a data challenge from Michigan Data Science Team (MDST).

The Michigan Data Science Team (MDST) and the Michigan Student Symposium for Interdisciplinary Statistical Sciences (MSSISS) have partnered with the City of Detroit to help solve one of the most pressing problems facing Detroit - building deterioration. Blight violations are issued by the city to individuals who allow their properties to remain in a deteriorated condition. Every year, the city of Detroit issues millions of dollars in fines to residents and every year, many of these fines remain unpaid. Enforcing unpaid blight fines is a costly and tedious process, so the city wants to know: how can we increase blight ticket compliance?

This project aims to take information on issuances of past tickets to build a model that can predict the likelihood of new ticket issuances paying their fine or not. It also evaluates the model, providing useful information on relevant indicators of blight ticket compliance or avoidance. 

Our data comes from the Detroit Open Data Portal (https://data.detroitmi.gov/) and comes with two files: past_blight_tickets.csv and current_blight_tickets.csv.

After data cleaning, we fit three models using the sklearn library and evaluate each model's preformance. We then chose the best model and export our predictions.
