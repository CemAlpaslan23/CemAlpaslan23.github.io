# Operations Research & Optimisation Graduate
### About Me
I hold a BSc in Industrial Engineering with a minor in Finance (Quantitative and Actuarial Finance) from Sabancı University and an MSc in Industrial Engineering from Curtin University, with a strong focus and technical background in operations research and optimisation. I specialise in mathematical modelling, algorithm development, and the implementation of heuristic and meta-heuristic methods to solve complex real-world optimisation problems.

My academic and project work focuses on logistics, production systems, scheduling, and financial optimisation, with a current emphasis on operations research applications in the mining, energy, and transportation sectors. Beyond this, I am passionate about learning and integrating machine learning and artificial intelligence techniques to develop advanced analytics solutions for real-world optimisation challenges. Furthermore, I am passionate about improving my programming skills and learning new languages and tools.

I am committed to continuous learning and highly motivated to further develop my skills through graduate employment opportunity.

### Education

- **M.Sc. Industrial Engineering**  
  Curtin University, Perth/Western Australia *(2024 – 2026)*  

- **B.S. Industrial Engineering**  
  Sabancı University, Istanbul/Turkey *(2018 – 2023)*  

- **Minor in Finance**  
  Sabancı University, Istanbul/Turkey *(2020 – 2023)*
 
### Projects

#### Routing Optimisation for Freight Operations (Master’s Thesis - Ongoing) 	 January 2026 – June2026 

- Currently developing routing optimisation strategies for an Australian freight company to improve operational efficiency under real-world logistical constraints.
- Developing a cost-minimizing mathematical model for a multi-trip pickup and delivery vehicle routing problem with vehicle rental, capacity, time window, distance, and inventory constraints and designing efficient solution algorithm for large-scale real-world instances.
  
#### Drill and Blast Optimisation for Open-pit Mines (Master’s Project) 	 July 2025 – November 2025

- Analysed and extended an existing drill-and-blast optimisation article called "Drill Pattern Optimisation for Large Complex Blasts to Improve Fragmentation and Dig Efficiency" by formulating a large-scale non-linear mathematical model incorporating fragmentation-based objective functions and operational constraint.
- Modelled complex open-pit bench characteristics including blast geometry, explosive parameters, and rock mass variability to realistically represent industrial drilling and blasting conditions.
- Designed a synthetic data generation algorithm to simulate bench geometry, spatial hardness distributions, and blast hole configurations, enabling scalable and controlled computational experiments.
- Developed an adaptive Particle Swarm Optimisation (PSO) metaheuristic with dynamic parameter tuning and restart mechanisms to efficiently solve the established non-linear mathematical model.
- Achieved up to 13.7% improvement in total fragmentation objective and 12.8% reduction in maximum fragmentation ratio objective, demonstrating the effectiveness of the proposed optimisation methodology.
  
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

- A heterogeneous vehicle routing scenario was modelled to represent last-mile delivery operations in a large urban environment (Anatolian side of Istanbul). The system included a fleet of 32 vehicles with different capacity profiles (trucks and vans), the purpose was reducing the number of vehicles used and improving the total cost and the total distance traveled with respect to certain operational constraints.
- K-means clustering algorithm was developed and applied for ensuring non-empty clusters and operational feasibility.
- Implemented capacity-aware cluster validation and refinement mechanisms to the k-means clustering algorithm incorporating demand-capacity checks, maximum service limits per route, demand-based vehicle assignment, and controlled cluster splitting and merging.
- Clusters which were created with the k-means function were sorted from largest to smallest according to their demand values, and the clusters with the highest demand values were planned to be assigned to trucks and the remaining ones to vans.
- Clusters exceeding the vehicle capacity and maximum number of nodes per cluster were divided into sub-clusters, ensuring that they did not exceed the vehicle capacity and number of points. Established subclusters were defined as big and small according to the number of customers in the clusters, and big and small clusters were merged.
- With the adjusted K-means algorithm, the number of clusters, which was initially 32, was reduced to 28; therefore, a significant improvement was made in the number of vehicles used and the total cost.
- Formulated a Traveling Salesman Problem (TSP) mathematical model for each feasible cluster by defining sets, parameters, decision variables, objective function, and constraints to minimise total travel distance and cost.
- Established clusters with the adjusted K-means algorithm were inserted into the TSP mathematical model code to find the optimal visiting sequence for each cluster. TSP mathematical model was coded using Python, and Gurobi was used as an optimization solver tool.

#### Optimisation of Parallel Machine Scheduling using Genetic Algorithm	February 2024 – April 2024

- Genetic algorithm which is a well-known metaheuristic approach inspired by the process of natural selection that iteratively evolves a population of candidate solutions using operations like crossover and mutation to find approximate solutions to complex problems was used as the main optimisation solver for the parallel machine scheduling problem.
- Developed and implemented a Genetic Algorithm in Python to optimise production scheduling by minimising total job tardiness under multiple operational constraints, including processing times, setup times, due dates, order quantities, machine availability, and capacity limitations.
- Designed a tardiness-based fitness function and implemented a parameter evaluation framework to analyse the impact of population size, mutation rate, and number of generations, enabling selection of high-performing algorithm configurations.
- Implemented evolutionary search procedures including customised crossover and mutation operators, along with feasibility control mechanisms to ensure machine capacity and working time constraints were satisfied throughout the optimisation process.
- Generated optimised production schedules across multiple generations and analysed convergence behaviour to evaluate scheduling performance improvements.
- Developed detailed schedule visualisations using Gantt charts to represent machine assignments, processing intervals, and sequencing structure.
- Produced comprehensive scheduling outputs including job start times, completion times, and tardiness metrics to support performance evaluation and decision analysis.
  
#### Vehicle Routing Optimisation with Backhaul Clusters	December 2023 – January 2024

- Developed a vehicle routing optimisation with backhaul operations to model urban logistics (European side of Istanbul) under realistic operational constraints, including delivery and pickup locations, vehicle capacities, time windows, and working time limits.
- Mixed integer linear programming model was established by identifying the sets, parameters, decision variables, objective function and constraints with a goal of minimizing the total distance traveled and the total cost.
- Developed constraints ensured that each customer is visited exactly once, each route starts and ends at the depot, flow/balance, time window requirements are met, vehicle capacity limitation is enforced, customer demands are satisfied, backhaul cluster requirements are fulfilled, deliveries are done before pickups, vehicle loads are updated after pickup and delivery operations, and legal working hours of each vehicle are not exceeded.
- The mathematical model was coded using Python, Gurobi was used as the optimisation solver tool and established routes were visualized.
- 2-opt Algorithm, a local search algorithm, was implemented for route optimization (distance reduction) with a goal of enhancing the efficiency of the initial solution.
- Tkinter-based user interface for real-time visualization was developed, allowing users to observe the routing process interactively. Next destination, previous destination, vehicle capacity, load on the vehicle, and delivered/picked-up demand values were provided in the Tkinter-based user interface to the users.
  
#### Last-mile Deliveries Using Autonomous Robots (Graduation Project)	September 2022 – June 2023

- The main objective of this project is to develop an optimisation-based solution methodology for Coffy, a coffee company operating on the Sabancı University campus, utilising autonomous robots for last-mile delivery operations.
-	Diverse types of companies which are using electrical autonomous robots in their delivery process were investigated and some parameter values such as robot cargo capacity, cost of each robot, battery capacity of each robot, and energy consumption rate per kilometer were determined and calculated.
-	The problem was looked from a routing viewpoint and deal with the problem as an extension of the well-known Vehicle Routing Problem (VRP) and integrated in the Sabanci University map.
-	Provided dataset which includes 15 customer locations and depot, Latitude, Longitude, Demand, and Time Window values of those locations evaluated, and Haversine Distance calculation method was used to determine the distances between customer locations.
-	Mixed integer linear programming model was developed by identifying the sets, parameters, decision variables, objective function and constraints with a goal of minimizing the total distance traveled and the total cost.
-	Developed constraints ensured that each customer is visited exactly once, each route starts and ends at the depot, flow/balance, time window requirements, ensuring the vehicle capacity limitation, meeting customer demands and battery capacity of the electrical vehicles are not violated.
-	Established mathematical model was coded by using Python as a programming language and Gurobi was used as an optimization solver tool in the project.
-	The problem was modeled and solved within the Sabanci University map, and formed routes were visualized to provide better outcomes for the company.
-	Additionally, Savings Heuristic was adjusted by considering the vehicle capacity, battery capacity, and time window restrictions of the clients.
-	The developed Savings Heuristic was coded using the Python programming language.
-	Adjusted Savings Heuristic Algorithm was modeled within the Sabanci University map and formed routes were visualized.
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
