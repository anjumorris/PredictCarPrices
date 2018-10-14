# Predicted Pre-owned Car Prices

### Project Luther

> #### Datasets
Web scrapping from www.carmax.com
>  1.  1700 + webscraped data points
>  2.  30+ parameters



> #### Tools
>
> 1. Numpy
> 2. Pandas
> 3. Matplotlib
> 4. Seaborn
> 5. Selenium
> 6. Statsmodel
> 7. Sklearn
> 8. Powerpoint
> 9. Typora
> 10. Jupyter Notebooks



> #### Algorithms
>
> 1. Simple linear regression
> 2. Lasso and Ridge Regression
> 3. Cross-validation



> #### Modules 
>
> 1. **data_collection** - contains notebooks for web scrapping 
>
>    1. **grab_links.ipynb** 
>
>       This notebook goes to the carmax website and grabs basic information on the cars from their banners. We typically have 50 banners per page after which it goes to the next button to keep pulling 50 banners at a time automatically. Most importantly it grabs the stockno (viz the unique identifier for a car).  Using this stockno we can generate links to the car's individual page. 
>
>    2. **page_scrap.ipynb**
>
>       This notebook creates go to a car's individual page by generating the link "https://www.carmax.com/car/"+ str (stock_num). It goes to this page and scraps the key details such as miles, color and then clicks on "see all  specifications" which 
>
> 2. 
>
>    1. data_collection - contains notebooks for web scrapping 
>
>       1. grab_links.ipynb 
>
>          This notebook goes to the carmax website and grabs basic information on the cars from their banners. We typically have 50 banners per page after which it goes to the next button to keep pulling 50 banners at a time automatically. Most importantly it grabs the stockno (viz the unique identifier for a car).  Using this stockno we can generate links to the car's individual page. 
>
>       2. page_scrap.ipynb
>
>          This notebook creates go to a car's individual page by generating the link "https://www.carmax.com/car/"+ str (stock_num). It goes to this page and scraps the key details such as miles, color and then clicks on "see all  specifications" which 
>
>    2. data_cleaning
>
>       1. clean_data.ipynb
>
>          Notebook that cleans all my data and outputs to final_data.csv
>
>       2. encoding_data.ipynb
>
>          This notebook reads the final_data.csv and prepares model_data.csv which can be used to run models. The notebook encodes categorical features such as 
>
>          - brand - luxury or not 
>          - interior_color - black or not
>          - exterior_color - dark colors (black, brown ..), light colors (white, silver ..), prime colors (red, gold,blue ..
>          - engine_type (normal, turbo or alternate)
>
>    3. model
>
>       1. explore_correlations.ipynb
>
>          Explore  the data, look at correlations and try feature engineering
>
>       2. model_1_linear_regression.ipynb
>
>          Prepare multiple linear regression models and figure out which feature to remove / transform.
>
>       3. model_2_final.ipynb
>
>          1. 
>
>    4. data
>
>       1. final_data.csv
>       2. model_data.csv
>
>    5. docs - all documents pertaining to the project
>
>       1. Proposal.pages / Proposal.pdf
>
>          Initial proposal idea  
>
>       2. PREDICTING USED CAR PRICES.pdf
>
>          Presentation on the Project
>
>       3. Summary.pages / Summary.pdf
>
>          Final summary for the project
>
> 3. 1. **clean_data.ipynb**
>
>       Notebook that cleans all my data and outputs to final_data.csv
>
>    2. **encoding_data.ipynb**
>
>       This notebook reads the final_data.csv and prepares model_data.csv which can be used to run models. The notebook encodes categorical features such as 
>
>       - brand - luxury or not 
>       - interior_color - black or not
>       - exterior_color - dark colors (black, brown ..), light colors (white, silver ..), prime colors (red, gold,blue ..
>       - engine_type (normal, turbo or alternate)
>
>    3. **data**
>
>       1. final_data.csv
>
>          cleaned data 
>
>       2. Model_data.csv
>
>          encoded data that is ready for modelling
>
>    4. **model**
>
>       1. **explore_correlations.ipynb**
>
>          Explore  the data, look at correlations and try feature engineering
>
>       2. **model_1_linear_regression.ipynb**
>
>          Prepare multiple linear regression models and figure out which feature to remove / transform.
>
>       3. **model_2_final.ipynb**
>
>          Lasso and Ridege crossvalidation, compare several models and select best model. Test the model.
>
>    5. **model**
>
>    6. explore_correlations.ipynb **
>
>       Explore  the data, look at correlations and try feature engineering
>
>    7. model_1_linear_regression.ipynb
>
>       Prepare multiple linear regression models and figure out which feature to remove / transform.
>
>    8. model_2_final.ipynb
>
>       1. datafinal_data.csvmodel_data.csv
>
> 4. 1. final_data.csv
>
>    2. model_data.csv
>
>    3. docs - all documents pertaining to the project
>
>    4. Proposal.pages / Proposal.pdf
>
>       Initial proposal idea  
>
>    5. PREDICTING USED CAR PRICES.pdf
>
>       Presentation on the Project
>
>    6. Summary.pages / Summary.pdf
>
>       Final summary for the project
>
>

> #### How to run ?
>
> 1. Run only the Module - "model" as the others are related to web scrapping and cleaning of the data. Their ouput is stored in the data files - final_data.csv and model_data.csv 

