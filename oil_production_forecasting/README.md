# Choice of location for the oil rig

Let's say you work for the mining company GlavRosGosNeft. We need to decide where to drill a new well.

You have been provided with oil samples in three regions: in each of 10,000 deposits, where the quality of oil and the volume of its reserves have been measured. Build a machine learning model to help determine the region where mining will bring the most profit. Analyze possible profits and risks using the *Bootstrap.* technique

Steps to choose a location:

- In the selected region, they are looking for deposits, for each, the values ​​of the signs are determined;
- Build a model and estimate the volume of reserves;
- Select the deposits with the highest value estimates. The number of fields depends on the company's budget and the cost of developing one well;
- The profit is equal to the total profit of the selected deposits.

Conditions of the problem:
- Only linear regression is suitable for training the model (the rest are not predictable enough).
- When exploring the region, 500 points are explored, from which, using machine learning, the best 200 are selected for development.
- The budget for the development of wells in the region is 10 billion rubles.
- At current prices, one barrel of raw materials brings 450 rubles of income. The income from each unit of the product is 450 thousand rubles, since the volume is indicated in thousands of barrels.
- After assessing the risks, you should leave only those regions in which the probability of losses is less than 2.5%. Among them, choose the region with the highest average profit

## Tools/Libraries

*Python,* *Pandas,* *Scikit-learn,* *Bootstrap*
