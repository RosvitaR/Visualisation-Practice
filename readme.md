# Prosper Loan Data Analysis
## by Rosvita Robnik


## Dataset

The dataset I have been investigating belongs to Prosper's peer-to-peer platform that connects borrowers and lenders. It contains 113,937 loans with 81 variables on each loan, that are related to loan details (e.g. interest rate, amount, length, etc.), borrowers' data (e.g. occupation, home-ownership, credit rating, etc.) and some other kind of data (e.g. number of investors for a loan).
Before I bit into exploration, I had performed a quick visual and programmatic assessment in order to pick up a dozen variables to explore.


## Summary of Findings

I tried to explore the data from two perspectives, the main one in a role of a lender, and the side one as a potential borrower.
The univariate exploration of the dataset gave me some general information:
- the most frequent loan amounts are 4k, 15k and 10k, the lowest amount is 1k, the highest 35k and the average one USD 8337;
- a loan term is either 12, 36 or 60 months, more than three quarters in duration of 36 months and less than a quarter in duration of 60 months;
- there are approximately half of home-owners among the borrowers;
- the most borrowers come from California;
- none of borrowers' occupation stands out;
- the most frequent reasons for a loan are not encouraging for a potential lender;
- borrowers' rating is close to simmetrical;
- more than a half of borrowers earn between USD 25k and 75k, most of them are employed;
- lenders' yield is extremely high;
The bivariate exploration of the dataset revealed the relationships as follows:
- the average yield slightly differ according to the loan purpose;
- linear dependence between the lender's yield and borrower's rating with plenty of outliers
- the number of investors has no impact on the yield;
- strong linear correlation between the yield and borrower's rate;
- the employment status has an impact on the rate at the unemployed borrowers and on the ones with unknown status;
- at some points the borrower's rating is not in accordance with their income;
- borrowers with the lower rating can raise lower loans;
- the interest rate slightly falls with the amount raising;
The multivariate exploration widened previous findings:
- the borrowers with worse rating can raise lower loans and should pay higher interest rate;
- the effective yield is in linear relation with the borrower's rate, but firmly influenced by the borrower's rating;
- the relationship between yield and rating has numerous outliers at the 36-months term.

In a word, as a potential lender I could choose between the high risk investment with higher yield and more safe investment with lower yield.
From a potencial borrower perspective I can count on an expensive loan (the average interest rate is almost 20%!).


## Key Insights for Presentation

In the presentation, I would like to present some facts that every potential lender should know before investing into loans. The focal part of the presentation is yield and its relationship with borrowers' rates and ratings.
The first graph, a histogram, displays a distribution of the yield.
The second plot, box plots, reveal the relationship between yield and ratings, taking into account the length of the loans. As opposed to the exploratory, I use for the presentation estimated effective yield - it is more realistic, since it takes into consideration two more calculations.
The third plot, a scatter plot, displays in what relations are yield, rate and rating.

