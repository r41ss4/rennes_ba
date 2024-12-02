# About the Project 
This is a project for the subject Business Analytics at Rennes School of Business. It aims to analyze rating factors and other values related to the platform content. By doing so, we hope to determine which movies and series should remain available on the Netflix platform. We will use three datasets (data_n1, data_n2, data_n3 and data_n4) related to Netflix content to perform data cleaning, descriptive analysis, and other methods.

## Team member
*   **[Kuan-Yu HOU](https://github.com/DoreenHou)** 
*   **[María Teresa Higareda](https://github.com/Teresiux14)**   
*   **[Samantha Ramos](https://github.com/samanta-ramos)**
*   **[Yi-Hsin TUNG](https://github.com/evatung0719)**
*   **[Xian Harding Anglés](https://github.com/r41ss4)**
## The Dataset
The datasets have been obtained through **[Kaggle](https://www.kaggle.com/)** platform and selected to provide relevants insights regarding flights pricing. 
*   **data_n1:** It includes a wide range of movies available on Netflix and their features, such as movies title, cast of the movie, desc of movies, duration, rating on IMDB, voted by people, year, genre, certificate. It was extracted from **[Netflix popular movies dataset](https://www.kaggle.com/datasets/narayan63/netflix-popular-movies-dataset)**     
*   **data_n2:** It contains information about 1,000 shows available in Netflix over the last years, the gathering method took advantage of the Netflix’s suggestion engine. It was extracted from **(1000 Netflix Shows)[https://www.kaggle.com/datasets/chasewillden/netflix-shows]** 
*   **data_n3:** It includes a wide range of features and variables, such as movies title, cast of the movie,desc of movies, duration, rating on IMDB from a different source. It was extracted from **[Netflix Dataset for Analysis](https://www.kaggle.com/datasets/yaminh/netflix-dataset-for-analysis)**    
*   **data_n4:** It includes a wide range of features and variables titles available in netflix. It was extracted from **[Netflix Movies and TV Shows](https://www.kaggle.com/datasets/dgoenrique/netflix-movies-and-tv-shows?select=credits.csv)**

## Folders and organization 
```
rennes_ba/          
│           
├── data/         
│   ├── raw/                   
│   │   ├── data_n1.csv   
│   │   ├── data_n2.csv  
│   │   ├── data_n3.csv              
│   │   └── data_n2.csv     
│   ├── cleaned/        
│   │   ├── clean_datan1.csv   
│   │   ├── clean_datan2.csv        
│   │   ├── clean_datan3.csv        
│   │   └── clean_datan4.csv            
│   └── merged/         
│       └── merged_data.csv           
│                       
├── notebooks/                    
│   ├── descriptive.ipynb         
│   ├── cleaning.ipynb          
│   ├── diagnostic.ipynb 
│   ├── merging.ipynb          
│   ├── predictive.ipynb      
│   └── prescriptive.ipynb                
│       
├── .ipynb_checkpoints/     
├── .jupyter/           
├── .virtual_documents/         
├── .DS_Store               
└── README.md          
```

## Methodology
**1. Data Cleaning:** We will preprocess the datasets to handle missing values, outliers, and inconsistencies.          
**2. Exploratory Data Analysis (EDA):** Conduct visualizations and statistical analyses to understand relationships between ticket prices and other variables.      
**3. Descriptive Analytics:** Generate summary statistics to provide insights into the datasets.     
**4. Diagnosic Analysis:** Investigate root causes of observed patterns and anomalies in the data.      
**4. Predictive Analytics:** Build predictive models to estimate ticket prices based on the identified factors.     
**5. Prescriptive Analytics:** Develop optimization models to recommend pricing strategies that maximize revenue or market share.  

## Conclusions
Feel free to review our findings in the file **[Insights.md](https://github.com/r41ss4/rennes_ba/blob/main/Insights.md)**. For more information, there is a full report available by request to team members of the project. 

## Tools and Technologies
- Python 
- Jupyter Notebook
- Kaggle
- Visual Studio Code 
- GitHub repository


