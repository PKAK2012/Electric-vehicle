# Electric-vehicle

This dataset contain the details for Electric car and its include Vin (1-10), County, City, State, Postal Code, Model Year, Make, Model, Electric Vehicle Type, Clean Alternative Fuel Vehicle (CAFV) Eligibility, Electric Range, Base Msrp, Legislative District, Dol Vehicle Id, Vehicle Location, Electric Utility, 2020 Census Tract

Objective:
The objective of this dataset is perdict the CAFV Eligibility(Clean Alternative Fuel Vehicle) of the car

Column Description:
Vin (1-10) – The first 10 characters of the Vehicle Identification Number (VIN), a unique identifier for each vehicle.
County – The county where the vehicle is registered.
City – The city where the vehicle is registered.
State – The state where the vehicle is registered (e.g., WA for Washington).
Postal Code – The postal (ZIP) code where the vehicle is registered.
Model Year – The manufacturing year of the vehicle.
Make – The manufacturer or brand of the vehicle (e.g., Tesla, Nissan, BMW).
Model – The specific model of the vehicle (e.g., Model S, LEAF, i3).
Electric Vehicle Type – The type of electric vehicle:
Battery Electric Vehicle (BEV) – Fully electric vehicle with no gasoline engine.
Plug-in Hybrid Electric Vehicle (PHEV) – A vehicle that uses both electricity and gasoline.
Clean Alternative Fuel Vehicle (CAFV) Eligibility – Whether the vehicle is eligible for Clean Alternative Fuel Vehicle (CAFV) incentives or not. Categories may include:
"Clean Alternative Fuel Vehicle Eligible"
"Not eligible due to low battery range"
Electric Range – The estimated number of miles the vehicle can travel using only electric power.
Base MSRP – The Manufacturer’s Suggested Retail Price (MSRP) of the vehicle without additional options.
Legislative District – The legislative district where the vehicle is registered.
DOL Vehicle ID – A unique identifier assigned by the Department of Licensing (DOL) for the vehicle.
Vehicle Location – The geographic coordinates (latitude and longitude) of the vehicle's registration location.
Electric Utility – The electric utility company that provides service to the vehicle’s registered location.
2020 Census Tract – The Census Tract from the 2020 U.S. Census, which helps in demographic and policy analysis.

Machine Learning Type is Supervisied Learning: This dataset is suitable for Supervisied Learning the CAFV column is identified as the target variable because it depends on all other features, while the remaining columns serve as independent variables.

Categorized Type: The "CAFV Eligibility" column contains categories such as "Clean Alternative Fuel Vehicle Eligible" and "Not eligible due to low battery range," making it appropriate for classification tasks.

Conclusion
This dataset is well-suited for Supervised Learning, specifically for a Classification task, where the goal is to predict the CAFV Eligibility of a vehicle based on its features. By leveraging various machine learning models, we can gain insights into the factors influencing eligibility and potentially improve policy decisions related to clean alternative fuel vehicles.

