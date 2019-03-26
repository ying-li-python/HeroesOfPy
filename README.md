
<img src="https://images.unsplash.com/photo-1548686304-89d188a80029?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1350&q=80" height="80%" width="80%"> 

# HeroesOfPy

To understand gaming trends, we would like to report data analytics using the Pandas module of Python. In this example, we observed the purchasing trends of players who play "Heroes of Pymoli".

## Prerequisites
- Python 
- [Pandas](https://pandas.pydata.org/) (Python module) 
- [Jupyter Notebook](https://jupyter.org/) 
- Bonus: [matplotlib](https://matplotlib.org/) 

## Getting started 
Download this folder and in this folder, run Jupyter Notebook. This will open a new window on your browser. 

Example:
```
git clone https://github.com/ying-li-python/HeroesOfPy.git
cd HereosOfPy 
jupyter notebook 
```

## Resources  

- Purchase data under Resources were kindly provided by UC Berkeley's Data Analytics and Visualization 

## Results 

Several metrics were performed in Jupyter Notebook using Pandas to determine: 
- how much profit the game makes by item purchases 
- the distribution of players by age and gender 
- the gender group that is likely to play the game (and purchase an Item) 
- the age group is likely to play the game (and purchase an Item)
- top players who spend the most in the game
- most popular item purchases in the game

## Results Discussion 

We can describe three important trends based on the results as observed in our Jupyter Notebook.


##### Figure 1. Percentage of Players by Gender 

  <img src="https://raw.githubusercontent.com/ying-li-python/HeroesOfPy/master/Images/gender_percent.png"> 
    
##### Table 1. Item Purchases by Gender

  <img src="https://raw.githubusercontent.com/ying-li-python/HeroesOfPy/master/Images/gender_purchase_summary.png">

 
Figure 1 results show that among players, males represents the highest gender group, comprising 84% of players, as compared to that of females, which at 14%, and other/non-disclosed, which are less than 2%. Consistent with this, Table 1 shows that males have the highest number of Item purchases and thereby, the greatest revenue from the Item purchases as compared to that of females and other/non-disclosed. 

In contrast, however, females spend more for Item purchases on average, despite significantly less number of Item purchases, as compared to that of males and other/non-disclosed, suggesting that females are likely to pay more for one item than pay for less for multiple items to improve their experiences during gameplay.

##### Figure 2. Percentage of Players by Age Group  

<img src="https://raw.githubusercontent.com/ying-li-python/HeroesOfPy/master/Images/age_group_percentages.png"> 



##### Table 2. Item Purchases by Age Group 

<img src="https://raw.githubusercontent.com/ying-li-python/HeroesOfPy/master/Images/age_group_purchase_summary.png">


Figure 2 results show that among the eight age groups, the majority of players are between ages 20-24, comprising almost 50% of all players in the game. Similarly, Table 2 shows that players who are aged 20-24 have the highest number of Item purchases and, therefore, the greatest revenue from Item purchases. 

Interestingly, despite having significantly lower number of Item purchases, players aged 35-39 spend the most money on average per Item purchase as well as paying significantly more per Item than any other age group, suggesting that these players are willing to spend more money to improve their experiences when playing the game.


##### Figure 3. Top Spenders of Item Purchases 

<img src="https://raw.githubusercontent.com/ying-li-python/HeroesOfPy/master/Images/top_spender_summary.png"> 

##### Table 3. Most Popular Item Purchases 

<img src="https://raw.githubusercontent.com/ying-li-python/HeroesOfPy/master/Images/most_profitable_summary.png">

Figure 3 results show that overall, a player will pay for at least one Item but no more than five Items, demonstrating that perhaps three or less Items purchases are sufficient for players to play the game. Interestingly, Table 3 shows that players prefer paying for a fairly expensive Item to enhance their gaming experience. 

Collectively, these data suggest that each player is willing to spend money on at least one Item, and how motivated they are to pay for an Item depends on their own personal gaming experience, not the cost of the Item.

#### Author 
Ying Li 

#### Acknowledgements 
- UC Berkeley's Data Analytics and Visualization
