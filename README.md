**A SOCIO-ECONOMIC STUDY OF DETERMINANTS OF PUBLIC HEALTH**

Milestone 1 repo for SIADS Q1-2024 student group of Anuvrat, Mike and Alex (09-anuvrat-mselesko-alehan-2024winter)
Project proposal available on Google drive at: https://docs.google.com/document/d/1ZP12Ck72LOGa7Z3ccDD5uAKn3ixGEmk5b7pTNjo7L_0/edit
Project report available on Google drive at: https://docs.google.com/presentation/d/181AvXBw_9uJlnWSkAYV06M7Fkq-lpnf-/edit#slide=id.g2b6ba6ad4c9_0_16
Tableau dashboard available at: https://public.tableau.com/app/profile/anuvrat.chaturvedi/viz/Milestone1-09-anuvrat-mselesko-alehan-2024winter/Home?publish=yes

The repo contains a single folder src that has Jupyter notebooks to be executed in this order and input data folder named 'data':

<ol>
  <li>input_data_exploration.ipynb - Loads the input CSV, Excels and pre-processes individual input files and pickles pre-processed inputs. </li>
  <li>data_merging.ipynb - Merges all the input files to create combined dataframes (primary i.e. ex-Florida and Florida). </li>
  <li>exploratory_data_analysis.ipynb - Analyzes pre-processed input dataframes and combined dataframes through summary statistics, histograms, etc. </li>
  <li>analysis.ipynb - Performs Correlation and PCA analyses.</li>
  <li>sdoh_population_analysis.ipynb - Looks at the relationship between SDOH measures and the preventative health measures.</li>
  <li>data_visualization.ipynb - In depth analysis and visualizaiton at a sub-national (state) level.</li>
  <li>regression.ipynb - Creates a basic linear regression model with General health as dependent variable. </li>
</ol>

The repo also contains following two helper notebooks that are called in other notebooks:

<ol>
  <li>helpers.ipynb</li>
  <li>utils.ipynb</li>
</ol>

The data subfolder contains following input files:

<ul>
  <li>ACSST5Y2022-S1901-Data.csv - Census income levels (American Community Survey: S1901 | Income in the past 12 months in 2022 Inflation-Adjusted Dollars)</li>
  <li>PLACES__Local_Data_for_Better_Health__ZCTA_Data_2023_release_20240127.csv - Health Outcomes (PLACES: Local Data for Better Health, ZCTA 2023 release)</li>
  <li>SDOH_Measures_for_ZCTA__ACS_2017-2021_20240121.csv - Social Determinants of Health (SDOH Measures for ZCTA, ACS 2017-2021)</li>
  <li>States Political Affiliations Jan-2024.xlsx - State Political Affiliation (Wikipedia Red States and Blue States)</li>
  <li>Per person state public health funding.csv - States Public Health Spending (SHADAC State Health Compare)</li>
  <li>ACSDP5Y2020.DP05-Data.csv - Racial composition (American Community Survey: DP05 | ACS Demographics and housing estimates)</li>
  <li>ZIP_TRACT_122023.xlsx - ZIP-State mapping (HUD-USPS ZIP-Tract cross walk)</li>
  <li>DECENNIALSF12000.H002-Data.csv - Urban-rural mapping (Decennial survey: H002 | Urban and rural)</li>
</ul>

The data subfolder also contains follwing processed pickled Pandas dataframes:

<ul>
  <li>df_income_1901_edited.pkl</li>
  <li>df_health_outcomes_edited.pkl</li>
  <li>df_sdoh_edited.pkl</li>
  <li>df_state_politics_edited.pkl</li>
  <li>df_state_public_spend_edited.pkl</li>
  <li>df_acs_edited.pkl</li>
  <li>df_zip2st_edited.pkl</li>
  <li>df_urban_rural_edited.pkl</li>
  <li>combined_dataset_nona.pkl (csv also available)</li>
  <li>combined_dataset_nona_florida.pkl (csv also available)</li>
  <li>ZIPs with gt 50 percent margin of error in median income.pkl (csv also available)</li>
</ul>
