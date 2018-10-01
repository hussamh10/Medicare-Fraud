# Medicare Fraud Detection
Medicare Fraud detection on Medicare aggregated data for Part D using variational autoencoders.

## Data Used:

### Part D Prescriber Data
This data gives details the  prescription drugs prescribed by individual physicians and other health care providers. The provider ID and Drug ID are the primary keys. This table only tells the stats regarding the provider and a drug. For example one sample row might be about Dr. X and Drug Y with other attributes being how many tablets were given, how many unique beneficiaries and etc.
Online samples for the data can be found [here](https://data.cms.gov/Medicare-Part-D/Medicare-Provider-Utilization-and-Payment-Data-201/3z4d-vmhm/data).
The [link](https://www.cms.gov/Research-Statistics-Data-and-Systems/Statistics-Trends-and-Reports/Medicare-Provider-Charge-Data/PartD2015.html) to the dataset.

All the preprocessing done to the data is present in the code. The data file is opened as is in the notebook.

Furthermore there is an additional file which provides the ids of the excluded providers (providers who were caught commiting fraud).
This file can be found [here](https://drive.google.com/open?id=1a2W_LeobihdnhV1iUnwgpFcA-abJTve6).


