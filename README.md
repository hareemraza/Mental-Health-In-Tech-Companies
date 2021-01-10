# Mental-Health-In-Tech-Companies


### Inspiration

The tech industry has observed a tremendous rise over the past decade whereby its growing advancements have made it a dream workplace for people around the globe. Consequently, a large influx of employees is observed in the tech-industry every year. However, the competitive and fast-paced environment does offer its own consequences. In this blog, we analyze the prevalence of mental health issues faced by employees in tech companies and the response from the perspective of both the employees and the companies in terms of the facilities provided to counter it.

### Goals

The driving question for our analysis is whether the organizational culture of tech companies affects the mental health of employees? If so, how do companies and employees respond to such issues? We divide our work into sub-questions such as the ones highlighted below:
- How does the nature of work affect the way an employee faces and responds to mental health issues?
- Does poor mental health affect productivity?
- How open are tech employees about their mental health in their workplace and what factors affect it?
- Do companies and employees differentiate between the way they deal with mental and physical health?
- How does the tech company accommodate its employees with mental health issues?

We will be answering them one by one, building one upon the other, and finally connecting the dots to reach a conclusion. But before that, let's have a quick look at the data we have.

### Dataset

Our dataset, titled “Mental Health in Tech Survey” is obtained from Open Sourcing Mental Illness, LTD. It is based on a single CSV file where each row represents an individual (tech company employee) who was surveyed in 2014 about his/her mental health and its correlation with various attributes.

### Key Steps

Following steps (in order) were involved in the entire process: 

- Data Cleaning
- Exploratory Data Analysis
- Machine Learning (KNN Classification)
- Statistical Inference
- Presentation

### Observations and Analysis

Although our data and its intent are thorough and it offers a multi-dimensional approach towards mental health in tech workspaces with categories such as openness about mental health, organizational structure and culture, and differences between mental and physical health, there is still a need for testing a few more important variables when we take mental health into consideration. Interestingly, none of the actual work factors had any significant impact on the mental health of employees. Instead, a lot of other confounding variables that we did not take into consideration could have made an impact.

We then notice that the dataset had several biases within itself. Demographically, it was dominated by responses from tech employees in the United States. Confounding variables such as high living costs, a competitive atmosphere, and high population density might have contributed to the increased mental health illnesses observed within the sample. Such factors were not accounted for in the survey. Similarly, the ratio of male to female was highly uneven, with little representation of the non-binary gender. Gender plays an important role in the experience of an individual in the tech workplace, and we observed trends of how male responses overshadowed those of females. Finally, we observed that the age peaked around 25 to 34. This is an unsettled period in an employee’s career where they find it difficult to adjust to the culture of the workplace. Thus, biases in the sample make it difficult for us to generalize findings to the greater population.

We also chose the data from 2014 because this survey was one of the first of its kind to report mental health issues in tech organizations. Therefore, it had many important features missing that could impact mental health significantly such as stress and anxiety. Similarly, it was not explicitly asked whether an employee suffers from mental health issues. Therefore, we had to infer it from the features that were available. Today, however, there might be a few changes in trends as this survey is conducted annually, with added features and questions that delve deeper into variables that have a direct impact on mental health. Such recent surveys when compared to those in the past could provide useful findings for both the tech and the medical industry. Similarly, our analysis could offer key insights for variables to consider that could shape future analysis of mental health issues in tech firms.

### Files

Following are the main files in this repository along with a short description of each:

- Datasets:
  - Tech.csv (Main dataset)
  - Cols.csv (Column descriptions)
  - data_tech.pkl (Cleaned data) 
- Notebooks:
  - DataCleaningAndEDA.ipynb (Stepwise and detailed implementation of data cleaning and in depth analysis)
  - KNN.ipynb (Implementation of KNN classifier and relevant machine learning models)
  - Statistical Inference.ipynb (Implementation of hypothesis testing)
- Presentation:
  - Presentation.pdf (Presentation slides highlighting the entire process, key findings and final conclusions)
  
  
### References

The dataset was obtained from [OSMI Mental Health in Tech Survey](https://osmihelp.org/research) from the year 2014 (the first every mental health survey in tech companies)

  
  
