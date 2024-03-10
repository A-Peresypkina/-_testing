# Bank_diploma

Good day, this research was made while I was studying in Yandex.
Purpose: conduct an analysis of the outflow of clients of Metanprombank

Stages: 
1) Predict the probability of churn (at the level of the next month) for each client;
2) Form typical client portraits: identify several of the most striking groups and characterize their main properties;
3) Analyze the main features that most strongly influence the churn;
4) Formulate the main conclusions and develop recommendations for improving the quality of work with clients:
    4.1. Identify target customer groups;
    4.2. Suggest measures to reduce outflow;
    4.3 Identify other features of interaction with clients.

Stack: pandas, numpy, seaborn, matplotlib, plotly, scipy, statsmodels

Сonclusions: 
1) A data analysis allowed to detect the main customer segments that were affected by churn were identified.
    - Segment 1: men with an account balance of more than 80,000 (3,551 people, 32.07% churn);
    - Segment 2: active clients with an estimated income (salary) of more than 50,000 (4,537 people, 25.85% churn);
    - Segment 3: bank clients with more than 2 bank products and credit scoring of more than 700 (6,621 people, 20.90% churn);

2) Were made recommendations for each segment:

|Sergemt|Recomendations|
|-------|--------------|
| #1 | 1) the ability to independently choose cashback categories (pay extra for choosing a specific category for a month); 2) among loyalty programs, offer more automotive topics (cashback for gasoline), programs related to real estate;|
| #2 | 1) higher % on the savings account; 2) offer a profitable salary transfer to the bank "Metanprombank" (in case of receiving a salary in another bank); 3) inform about new available banking products;|
| #3 | 1) offer special conditions for insuring property (auto, real estate); 2) credit card with a larger loan amount/longer loan repayment period; 3) the ability to independently choose cashback categories (pay extra for choosing a specific category for a month); 4) inform about new available banking products;|
