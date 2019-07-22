# AB_Test_Analysis
This is an AB test analysis for an e-commerce site to check if the site should incorporate the new changes made to the site or retain the old site keeping in mind the User navigation.<br>
The company has developed a new web page in order to try and increase the number of users who "convert," meaning the number of users who decide to pay for the company's product. 
The goal is to work through this notebook to help the company understand if they should implement this new page, keep the old page, or perhaps run the experiment longer to make their decision.<br>

The project is divided into 3 main parts:<br>
1. The probability
2. A/B Test
3. Regression
<br>

## Probability:
During this section we look out for various probabilities to ckeck what the current status is and what need to be done. 
This gives a clear statistic as to how it fares compared to the experiment that we do.
<br>

## A/B Testing: 
This is a hypothesis test that is carried to see how the changes fare over the existing product. Some of the questions that have been answered are:<br>
1. What is the conversion rate for  𝑝𝑛𝑒𝑤  under the null?
2. What is the conversion rate for  𝑝𝑜𝑙𝑑  under the null?
3. What is  𝑛𝑛𝑒𝑤 , the number of individuals in the treatment group?
4. What is  𝑛𝑜𝑙𝑑 , the number of individuals in the control group?
5. Simulate  𝑛𝑛𝑒𝑤  transactions with a conversion rate of  𝑝𝑛𝑒𝑤  under the null. Store these  𝑛𝑛𝑒𝑤 1's and 0's in new_page_converted.
6. Simulate  𝑛𝑜𝑙𝑑  transactions with a conversion rate of  𝑝𝑜𝑙𝑑  under the null. Store these  𝑛𝑜𝑙𝑑  1's and 0's in old_page_converted.
7. Create 10,000  𝑝𝑛𝑒𝑤  -  𝑝𝑜𝑙𝑑  values using the same simulation process you used in parts (a) through (g) above. Store all 10,000 values in a NumPy array called p_diffs.
<br>

## Regression: 
This is where we test if the results obtained in A/B test can also be obtained using the Regression tests. Once we notice that noth results match, it brings out the final result as to what should be implemented.
