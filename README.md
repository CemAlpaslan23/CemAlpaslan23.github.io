# Operations Research & Optimisation Graduate
### About Me
I hold a BSc in Industrial Engineering with a minor in Finance from Sabancı University and an MSc in Industrial Engineering from Curtin University, with a strong focus and technical background in operations research and optimisation. I specialise in mathematical modelling, algorithm development, and the implementation of heuristic and meta-heuristic methods to solve complex real-world optimisation problems.

My academic and project work focuses on logistics, production systems, scheduling, and financial optimisation, with a current emphasis on operations research applications in the mining, energy, and transportation sectors. Beyond this, I am passionate about learning and integrating machine learning and artificial intelligence techniques to develop advanced analytics solutions for real-world optimisation challenges. Furthermore, I am passionate about improving my programming skills and learning new languages and tools.

I am committed to continuous learning and highly motivated to further develop my skills through graduate employment opportunity.

### Education

- *M.Sc. Industrial Engineering**  
  Curtin University, Perth/Western Australia *(2024 – 2026)*  

- *B.S. Industrial Engineering**  
  Sabancı University, Istanbul/Turkey *(2018 – 2023)*  

- *Minor in Finance**  
  Sabancı University, Istanbul/Turkey *(2020 – 2023)*
 
### Projects

#### Routing Optimisation for an Australian Freight Firm (Master’s Thesis - Ongoing) 	 January 2026 – June2026 

- Currently developing routing optimisation strategies for an Australian freight company to improve operational efficiency under real-world logistical constraints.
- Developing a cost-minimizing mathematical model for a multi-trip pickup and delivery vehicle routing problem with vehicle rental, capacity, time window, distance, and inventory constraints and designing efficient solution algorithm for large-scale real-world instances.
  
#### Drill and Blast Optimisation for Open-pit Mines (Master’s Project) 	 July 2025 – November 2025

- Collected.
  
#### Portfolio Optimisation in Australian Mining and Metals (Master’s Project) 	 February 2025 – June 2025

- Collected daily financial data from Yahoo Finance for the period 2021–2025. The portfolio consisted of 11 assets including BHP.AX, FMG.AX, RIO.AX, EVN.AX, NST.AX, IGO.AX, PLS.AX, LTR.AX, SFR.AX, SVL.AX, and GOLD.AX (GC=F).  
- Preprocessed the dataset by removing outliers using Z-score filtering, handling missing values, and computing log returns to capture continuously compounded asset returns.  
- Performed exploratory data analysis (EDA), including price trend visualisation, trading volume analysis, return distributions, volatility patterns, and correlation matrices to evaluate diversification potential.  
- Implemented the Mean-Variance Model (Markowitz Portfolio Optimisation) to construct the Efficient Frontier, identify minimum-variance portfolios, and determine the Tangency Portfolio with the maximum sharpe ratio.  
- Developed the Black–Litterman Model by integrating market equilibrium returns with subjective investor views, generating more stable and diversified allocations compared to traditional mean-variance optimisation.  
- Applied the Risk Parity Portfolio approach to equalise asset risk contributions preventing over-concentration in highly volatile mining equities and improving diversification balance.  
- Formulated a Conditional Value-at-Risk (CVaR) Optimisation Model to minimise downside risk by controlling extreme losses beyond the Value-at-Risk threshold, suitable for risk-averse investors  
- Compared the performance of all four models (Markowitz, Black–Litterman, Risk Parity, CVaR) across key metrics such as expected returns, volatility, risk contribution, and tail-risk exposure.  
- Visualised results using the Efficient Frontier, portfolio allocation weight charts, and CVaR tail-loss distributions to clearly illustrate model differences.
- Provided investment strategy insights for investors who are interested in mining and commodity-focused financial assests.
  
#### Vehicle Routing Optimisation with Capacity-Aware K-Means Clustering	April 2024 – May 2024

- The logistics company delivers goods to customer locations on the Anatolian side of Istanbul with 32 vehicles, 2 of which are trucks, 30 of which are vans, and trucks and vans have different capacities. Instead of using all 32 vehicles, the company aims to have one vehicle visit a maximum of 35 customer points per day, with a goal of reducing the number of vehicles used and thus improving the total cost and the total distance traveled.
- Latitude, longitude, and demand values of customer locations in the dataset provided by the company were used in the project.
- K-means clustering function was developed for ensuring non-empty clusters and used to establish 32 clusters with all available vehicles, which includes all customer locations based on their geographical coordinates with `kmeans2` function from the SciPy library.
- Since the resulting clusters were created only with the k-means function, a new function was developed to evaluate the demand-capacity conditions and the conditions for a cluster to contain a maximum of 35 points.
- Clusters which were created with the k-means function were sorted from largest to smallest according to their demand values, and the clusters with the highest demand values were planned to be assigned to trucks and the remaining ones to vans.
- Clusters exceeding the vehicle capacity and maximum number of nodes per cluster were divided into sub-clusters, ensuring that they did not exceed the vehicle capacity and number of points. Established subclusters were defined as big and small according to the number of customers in the clusters, and big and small clusters were merged.
- With the adjusted K-means algorithm, the number of clusters, which was initially 32, was reduced to 28, and a significant improvement was made in the number of vehicles used and the total cost.
- Established clusters were visualized with the Matplotlib library, and the necessary print sections which show the cluster information were added to the project.
- Traveling Salesman Problem (TSP) mathematical model was established by identifying the sets, the parameters, the decision variables, the objective function, and the constraints with a goal of minimizing the total distance traveled and the total cost.
- Established clusters with the adjusted K-means algorithm were inserted into the TSP mathematical model code to find the optimal visiting sequence for each cluster. TSP mathematical model was coded using Python, and Gurobi was used as an optimization solver.
- Formed routes were visualized using the Matplotlib dictionary.

#### Optimisation of Parallel Machine Scheduling using Genetic Algorithm	February 2024 – April 2024

- Genetic algorithm is a well-known metaheuristic algorithm inspired by the process of natural selection that iteratively evolves a population of candidate solutions using operations like crossover and mutation to find approximate solutions to complex problems.
- Genetic Algorithm was developed and coded using Python. Libraries such as Pandas, NumPy, and Matplotlib were used with a goal of minimizing the total tardiness of jobs for a pharmaceutical company by considering processing times, setup times, due dates, order quantities, machine working times, and machine capacities.
- Fitness function in the algorithm was designed to minimize job tardiness, and an additional function was developed to evaluate different genetic algorithm parameters such as population size, mutation rate, and number of generations, and to select optimal parameters to achieve the best scheduling performance.
- Genetic algorithm was run to evolve job schedules over multiple generations. Crossover and mutation operations were developed according to the requirements of the algorithm to generate new offspring. An additional function was implemented to check machine capacities and working times for every generation.
- Gantt Chart was created to visualize job assignments on machines, displaying start times and end times of each job for each machine. Print sections including each job's start time, completion time, and tardiness values were added to the project.

#### Vehicle Routing Optimisation with Backhaul Clusters	December 2023 – January 2024

- Provided dataset which includes 44 customer locations (delivery points), 6 backhaul cluster locations (pickup points), and a depot on the European side of Istanbul. Latitude, longitude, demand, vehicle capacity, backhaul cluster capacity, cost of each vehicle, and time window values of those locations were evaluated. Haversine distance calculation method was used to determine the distances between customer locations.
- Mixed integer linear programming model was established by identifying the sets, the parameters, the decision variables, the objective function, and the constraints with a goal of minimizing the total distance traveled and the total cost.
- Developed constraints ensured that each customer is visited exactly once, each route starts and ends at the depot, time window requirements are met, vehicle capacity limitation is enforced, customer demands are satisfied, backhaul cluster requirements are fulfilled, deliveries are done before pickups, vehicle loads are updated after pickup and delivery operations, and legal working hours of each vehicle are not exceeded.
- The mathematical model was coded using Python. Libraries such as Pandas, NumPy, Matplotlib, Geopy, and Tkinter were used, and Gurobi was used as an optimization solver.
- Formed routes on the European side of Istanbul were visualized using the Matplotlib dictionary.
- 2-opt Algorithm, a local search algorithm, was coded for tour optimization with a goal of enhancing the efficiency of the initial solution.
- Total distance traveled by the mathematical model solution was reduced by the 2-opt algorithm, and established tours by the 2-opt algorithm were visualized using the Matplotlib dictionary.
- Tkinter-based user interface for real-time visualization was implemented, allowing users to observe the routing process interactively. Next destination, previous destination, vehicle capacity, load on the vehicle, and delivered/picked-up demand values were provided in the Tkinter-based user interface.

#### Last-mile Deliveries Using Autonomous Robots (Graduation Project)	September 2022 – June 2023

-	Diverse types of companies which are using electrical autonomous robots in their delivery process were investigated and some parameter values such as robot cargo capacity, cost of each robot, battery capacity of each robot, and energy consumption rate per kilometer were determined.
-	The problem was looked from a routing viewpoint and deal with the problem as an extension of the well-known Vehicle Routing Problem (VRP) and integrated in the Sabanci University map.
-	Provided dataset which includes 15 customer locations and depot, Latitude, Longitude, Demand, and Time Window values of those locations evaluated, and Haversine Distance calculation method was used to determine the distances between customer locations.
-	Mixed integer linear programming model was established by identifying the sets, the parameters, the decision variables, the objective function and the constraints with a goal of minimizing the total distance traveled and the total cost.
-	Developed constraints ensured that each customer is visited exactly once, each route starts and ends at the depot, time window requirements, ensuring the vehicle capacity limitation and meeting customer demands and battery capacity of the electrical vehicles are not violated.
-	Established mathematical model was coded by using python as a programming language. Libraries of Pandas, NumPy, Matplotlib and Geopy were used and Gurobi was used as an optimization solver in the project.
-	The problem was modeled and solved within the Sabanci University map, and formed routes were visualized by using the Matplotlib dictionary.
-	Additionally, Savings Heuristic was adjusted by considering the vehicle capacity, battery capacity, and time window restrictions of the clients.
-	The developed Savings Heuristic was coded using the python programming language.
-	Heuristic Algorithm was modeled within the Sabanci University map, and formed routes were visualized by using the Matplotlib dictionary.
-	The solution obtained by Mathematical Modelling and the solution obtained by Savings Heuristic were compared.
-	Lastly, Savings Heuristic was tested on 10 large instances by using the Euclidean Distance calculation method.


#### Detecting Fraudulent Activities in eBay Auctions	September 2022 – January 2023

-	Developed a machine learning-based fraud detection system for eBay auctions using Python and the Shill Bidding Dataset which includes features of the popular products for the eBay auctions.
-	The purpose of the project was to observe and analyze the effect of the given attributes in the dataset of different biddings to detect the fraud in eBay auctions and try to build a machine learning model to classify fraudulent activities in an eBay auction.
-	Performed exploratory data analysis (EDA), including correlation analysis, data visualization, and feature engineering to identify patterns associated with fraudulent bidding behaviour.
-	Conducted statistical analysis and hypothesis testing to evaluate the impact of bidding attributes on fraud classification.
-	Applied data preprocessing techniques, including feature scaling and normalization, to improve model performance and ensure consistent feature representation.
-	Implemented and compared multiple classification algorithms, including Logistic Regression, Decision Tree, Random Forest, and XGBoost, to detect fraudulent auction activities.
-	Evaluated model performance using appropriate classification metrics (e.g., accuracy, precision, recall, F1-score, ROC-AUC).
-	Performed hyperparameter tuning to optimise model performance and select the most effective classifier.

#### Warehouse Operations in Tire Manufacturing Company	September 2021 – January 2022

-	Developed a discrete-event simulation model of warehouse operations in a tire manufacturing company using Arena Simulation Software.
-	Defined system components including entities, attributes, resources, system states, queues, events, activities, and delays to accurately represent operational processes.
-	Conducted input data analysis using Arena Input Analyzer to fit appropriate probability distributions for customer check-in and check-out times based on historical data.
-	Performed pilot simulation runs (replications) to evaluate system behaviour and model performance.
-	Performed output analysis using the Output Analyzer tool of Arena and built 95% confidence intervals for performance measures of two alternative system designs.
-	Applied a paired t-test statistical comparison to evaluate alternative models and identify the superior operational configuration.
