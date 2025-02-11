Synthetic geospatial data has emerged as a transformative tool in urban analytics, 
particularly for contexts where granular, real-world data are unavailable or sensitive. 
Synthetic data replicates the statistical characteristics of real datasets while preserving 
privacy and avoiding reidentification risks. This approach has proven invaluable for 
applications in mobility analysis, infrastructure planning, and policy evaluation, offering a 
sandbox for "what-if" scenarios that are not feasible with real-world data alone.
In the context of cities in the Global South, such as Mumbai, the scarcity of detailed mobility 
data poses significant challenges for urban planning. Synthetic data generation provides a 
solution by simulating realistic, fine-grained urban behaviors. For instance, generating trip 
data for areas like Bandra in Mumbai requires adapting synthetic data techniques to reflect 
local travel patterns, socio-economic diversity, and infrastructural constraints. This entails 
the use of agent-based models, machine learning, and statistical simulations to produce 
data that align with real-world dynamics without relying on sensitive or unavailable datasets.
In this project, three scripts have been developed to generate synthetic trip data for Bandra. 
The first script constructs a synthetic population representative of Bandra’s demographic 
and socio-economic attributes. The second simulates mobility patterns using probabilistic 
models that incorporate land use, transit availability, and behavioral assumptions. Finally, 
the third script evaluates and calibrates the synthetic data by comparing aggregated metrics 
against limited available real-world data. Together, these scripts demonstrate how 
synthetic data can be leveraged to overcome data gaps and inform evidence-based urban 
planning in resource-constrained environments.



This repo contains the required R code to generate the data from simple point of interest dataset and a shapefile
