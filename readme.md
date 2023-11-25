# British Shorthair
Codename British Shorthair is a project to experiment and understand more about Singapore's Public Transport, specifically the bus network, through urban data science.

Some of the use cases of this project may include:
- Analysis and insights of bus routes, loading and trip times for planning 
- Improved bus arrival timing estimations
- Optimisation of bus schedules, etc.
- Democratisation of open data - Insights allowing citizens to understand more about the city 

## Planned Stages
- Data Collection
- Data Exploitation - Time-series Clustering, etc.
- Visualising Data
- Deriving Insights

## Setting Up
1. Clone this repository
2. Run pip install -r requirements.txt in the root folder
3. Obtain the LTA Datamall API Key [here](https://datamall.lta.gov.sg/content/datamall/en.html)
4. Create a .env file in the scripts folder and paste the following:
    ```
    API_KEYS = []
    ```
5. Insert the API Key(s) obtained from LTA Datamall into the list in the .env file with quotes

## Running
There is one script available at the moment for Data Collection, to run:
```
python scripts/target_BSArrival.py
```