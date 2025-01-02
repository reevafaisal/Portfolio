## Introduction

- Senior studying Data Science (B.S.) at the University of Michigan Ann Arbor
- Working on building end-to-end, a tutorial mode feature for Hazel at the [Future of Programming Lab](https://neurocy.notion.site/Future-of-Programming-Lab-241d162461a04064ae1fd9ae32bf4cb1) (PI: Cyrus Omar, Assistant Professor).
- Working on social network analysis on Blue Sky at [Blue Data Lab](https://www-personal.umd.umich.edu/~tiananw/lab.html) (PI: Tian An Wong, Assistant Professor)
).


---


## Projects

### Search Engine
#### [Project Info](https://reevafaisal.github.io/SearchEngine/) | [Demo](https://c5b0-2600-6c44-74f0-94d0-d488-6c6e-3fdd-db05.ngrok-free.app/) | 12/2024

- Built a scalable search engine similar to Google or Bing, for EECS 485.
- Includes information retrieval concepts like text analysis (tf-idf) and link analysis (PageRank), and parallel data processing with MapReduce.
- Uses a Service-Oriented Architecture to scale dynamic pages and web search.
- Creates a segmented inverted index of web pages using a pipeline of MapReduce programs.
- Built an Index server, a REST API app that returns search results in JSON format.
- Built a Search server, a user interface that returns search results just like Google or Bing.
    
Technologies: Python, SQL, Flask, HTML and CSS, JSON

### Performance Predictions in TB and HIV  
#### [Report](https://reevafaisal.github.io/Performance-Predictions-in-TB-HIV/index.html) | 11/2024 
- This project leverages logistic regression to measure the predictive performance of Case Detection Rate (CDR) in country-specific mortality outcomes for patients with a dual burden of Tuberculosis (TB) and Human Immunodeficiency Viruses (HIV). 
- Using data from the [Tuberculosis Burden by Country](https://public.tableau.com/app/sample-data/TB_Burden_Country.csv?_gl=1*jep8cy*_ga*MTk5ODg2MTIzMi4xNzMxOTM4NzQx*_ga_8YLN0SNXVS*MTczMjU0MjY2OS42LjEuMTczMjU0MjgyNC4wLjAuMA..) dataset, it evaluates the role of CDR in determining mortality-to-incidence ratios (MIRs).
- Feature engineering techniques such as logarithmic scaling and quantile transformation were applied to the baseline model to address data skewness and improve model performance.
- The final model demonstrated an improvement in AUC for dual-burden mortality predictions, emphasizing the importance of early case detection in mitigating public health challenges.

Technologies: Python, Pandas, Scikit-learn 

### MapReduce Framework
#### [Project Info](https://reevafaisal.github.io/MapReduce/) | 10/2024

- MapReduce framework in Python inspired by Google’s original [MapReduce paper](https://static.googleusercontent.com/media/research.google.com/en//archive/mapreduce-osdi04.pdf) for EECS 485.
- Executes MapReduce programs with distributed processing on a cluster of computers like AWS EMR, Google Dataproc, or Microsoft MapReduce.
- Includes program execution, distributed systems, fault tolerance, OS-provided concurrency facilities (threads and processes), and networking (sockets).
- Consists of a Manager which listens for user-submitted MapReduce jobs and distributes the work among Workers, and multiple Worker instances that receive instructions from the Manager and execute map and reduce tasks that combine to form a MapReduce program.

Technologies: Python, Madoop (Custom version of Hadoop)

### Insta485 Client-Side Web Application
#### [Project Info](https://reevafaisal.github.io/Insta485/) | [Demo](http://ec2-18-219-187-14.us-east-2.compute.amazonaws.com/) | 10/2024  
- Developed an Instagram clone as part of a three-project sequence for EECS 485, focusing on building client-side dynamic pages using JavaScript, React, and AJAX.
- Refactored the server-side logic from Flask into a REST API to handle asynchronous data requests, enabling real-time updates for user interactions such as likes, comments, and infinite scrolling without page reloads.

Technologies: Python, SQL, HTML, CSS, JavaScript, React, Flask, AWS 

### Travelling Salesman Problem
#### [Project Info](https://reevafaisal.github.io/TSP/) | 06/2024                                                                                                
- Applied branch and bound algorithm to solve TSP problem for complete weighted graph, used MST to get the lower bound for remaining cost, and explored various heuristic approaches to achieve a nearly-optimal solution, for EECS 281.
- To find the optimal tour, we started with our nearly optimal solution and then employed the brute-force method of exhaustive enumeration to achieve the optimal path while being time efficient. 

Technologies: C++
