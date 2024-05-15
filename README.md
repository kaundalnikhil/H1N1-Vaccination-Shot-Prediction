<h1>H1N1 Vaccination Shot Prediction</h1>
Objective is to perform a classification of whether a person will or will not take the H1N1 vaccine.
<h2>Data Collection</h2>
Data was collected from Centers for Disease Control and Prevention (National Public Health Agency of the United States). https://www.cdc.gov/nchs/nis/data_files_h1n1.htm<br>
The data is related to National 2009 H1N1 Flu Survey.<br>
Then the DAT file was decoded by using the r program provided on the website.<br>
After that the rdata file was converted to csv (included in rdata_to_csv.ipynb).<br>
Of the 170+ features, 39 were selected manually.<br>
7 of them are behaviour indicators,  3 are opinion indicators, 6 are related to concern towards the virus, 5  are related to the level of knowledge of H1N1 virus, and 17 are related to demographics.<br>
The selection of these features could have impaced a lot towards the prediction of the target variable.<br>
Vaccination.ipynb contains the first attempt<br>
Vaccination_final_iteration.ipynb contains the final code.<br>

