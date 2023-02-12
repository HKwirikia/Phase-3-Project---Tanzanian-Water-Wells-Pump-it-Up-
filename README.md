# Pump it Up: Water Well Functionality
## Phase 3 Project
# 1. Business Understanding
MSABI, one of the largest water, sanitation, and hygiene (WASH) non-profit organizations in Tanzania, has a mission to improve access to clean water for all communities in the country.

Despite their efforts, many water wells in Tanzania still face challenges such as being in need of repair or failing altogether, which limits access to clean water for the population.

And with a population of over 57 million, it is crucial to ensure that the country's water wells are functional and provide safe drinking water to the people.

The problem that MSABI faces is that they must prioritise their efforts and allocate resources effectively to address this issue.

But, currently, MSABU has limited information about the condition of water wells in the country making it difficult to determine which wells are most in need of attention.
# 2. Data Understandig
The project utilizes data from Taarifa and Tanzanian Ministry of Water. The data includes information on 59,400 waterpoints.

There are three datasets available for this project, the training set labels, the training set values, and the test set values.

The target variable is "status_group" which details the functionality of waterpoints. It is a ternary classification classified as functional, functional but in need of repair, or non-functional.

The dataset includes the following features:

* amount_tsh - Total static head (amount water available to waterpoint)
* date_recorded - The date the row was entered
* funder - Who funded the well
* gps_height - Altitude of the well
* installer - Organization that installed the well
* longitude - GPS coordinate
* latitude - GPS coordinate
* wpt_name - Name of the waterpoint if there is one
* num_private -
* basin - Geographic water basin
* subvillage - Geographic location
* region - Geographic location
* region_code - Geographic location (coded)
* district_code - Geographic location (coded)
* lga - Geographic location
* ward - Geographic location
* population - Population around the well
* public_meeting - True/False
* recorded_by - Group entering this row of data
* scheme_management - Who operates the waterpoint
* scheme_name - Who operates the waterpoint
* permit - If the waterpoint is permitted
* construction_year - Year the waterpoint was constructed
* extraction_type - The kind of extraction the waterpoint uses
* extraction_type_group - The kind of extraction the waterpoint uses
* extraction_type_class - The kind of extraction the waterpoint uses
* management - How the waterpoint is managed
* management_group - How the waterpoint is managed
* payment - What the water costs
* payment_type - What the water costs
* water_quality - The quality of the water
* quality_group - The quality of the water
* quantity - The quantity of water
* quantity_group - The quantity of water
* source - The source of the water
* source_type - The source of the water
* source_class - The source of the water
* waterpoint_type - The kind of waterpoint
* waterpoint_type_group - The kind of waterpoint

# 3. Modeling

# 4. Evaluation

# 5. Conclusion

Repo Navigation
* data/ <--- Well Data Provided by DrivenData
* Final Notebook - Jupyter Notebook.pdf <--- PDF of Final Notebook
* Final Notebook.ipynb <--- Final Project Jupyter Notebook
* Presentation.pdf <--- PDF of Project Presentation to the Tanzania Ministy of Water
* README.md <--- README.md that you are currently reading
