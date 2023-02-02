# gtbootcamp_team2_project1
Repo for Team 2 (Data Ninjas) project 1

Data from used from Kaggle dataset "Global Cost of Living"

We were interested in looking at this data because many of us may be looking for new employment opportunities and wanted to begin understanding where we may want to concentrate on when looking for jobs.

Questions that came to mind when we embarked on this project were:
    -how does cost of living vary by state
    -what are the main drivers for varying cost of living
    -does geography play a role in the cost of living

The data was pulled into a jupyter notebook & cleaned to include only cities in the US.  

The data was then organized to be able to used for analysis.

Visualizations & analysis were done in several jupyter notebooks.  The description of the notebooks in the repo
along with the inputs and outputs of those files are included below for reference.


Notebook:  Cost_of_liv_project.ipynb (data importing & cleaning)
    input file: cost-of-living_v2.csv (original dataset from Kaggle)
    output files: output_cost_of_living.csv  &  output_expense_breakdown.csv
    
Notebook:  state_v2.ipynb (utilized APIs to add state & population data)
    input file: output_expense_breakdown.csv
    output files: output_expense_breakdown_states_pop.csv  
    
Notebook:  Visualizations.ipynb (analysis & output of visuals of data)
    input file: output_expense_breakdown_states_pop.csv
    output files: visuals
    
Notebook:  Trending_Expense_by_State.ipynb (analysis & output of visuals of data)
    input file: output_expense_breakdown_states_pop.csv
    output files: visuals
    
Notebook:  Libby_visuals.ipynb (analysis & output of visuals of data)
    input file: output_expense_breakdown_states_pop.csv
    output files: visuals