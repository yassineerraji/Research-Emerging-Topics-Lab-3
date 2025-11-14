# Research-Emerging-Topics : Lab-3

## Data preparation

- Load Steel dataset from previous labs

- Create operational plants dataset for years 2020-2030 : use start date and end date columns to determine if a plant is operating in a given year. If the end date is missing assume plant is still operating.

## Case study: China

- Compute China’s country level utilization rate for steel (production/capacity) based on yearly production (World Steel Association report) and capacity (OECD report). 
A more granular approach consists in using technology level utilization rates (one for BF-BOF, the emissive technology and one for EAF, the less emissive technology).

- Attribute this utilization rate to each plant and derive plant level production.

- Collect emission factors for China for each technology (”Main production process” column) from the Internet (cf. Hasanbeigi report).

- Attribute an emission factor to each plant based on technology and derive plant level emissions by multiplying the emission factor with production.

- Aggregate plant level emissions at the company level.

- Project company level emissions into the near future. 
You may borrow ideas from the notebook on uncertainty quantification (in the current folder: uncertainty_quantification.ipynb)
