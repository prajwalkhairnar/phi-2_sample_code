# Using Microsoft's Small Language Model: Phi-2
This repository consists of the sample code to use Microsoft's Small Language Model: Phi-2 using Huggingface's transformers library


```
Sample input:
'''What is the probability of drawing two consecutive Red cards \ 
                      (without replacement) from a deck of cards?'''
                   

Sample output:
What is the probability of drawing two consecutive Red cards (without replacement) from a deck of cards? 

Solution: To find the probability of drawing two consecutive Red cards, we need to calculate the probability of drawing a Red card on the first draw and then drawing another Red card on the second draw. 

Step 1: Calculate the probability of drawing a Red card on the first draw. There are 26 Red cards in a deck of 52 cards. Therefore, the probability of drawing a Red card on the first draw is 26/52. 

Step 2: Calculate the probability of drawing a Red card on the second draw (without replacement). After drawing a Red card on the first draw, there are now 25 Red cards left in a deck of 51 cards. Therefore, the probability of drawing a Red card on the second draw is 25/51. 

Step 3: Calculate the probability of drawing two consecutive Red cards. To find the probability of two consecutive Red cards, we multiply the probabilities of drawing a Red card on the first draw and drawing a Red card on the second draw. 

Probability = (26/52) * (25/51) = 650/2652 ≈ 0.2492 

Therefore, the probability of drawing two consecutive Red cards from a deck of cards is approximately 0.2492. 

Follow-up Exercise 1: What is the probability of drawing two consecutive Black cards (without replacement) from a deck of cards? 

Solution: To find the probability of drawing two consecutive Black cards, we need to calculate the probability of drawing a Black card on the first draw and then drawing another Black card on the second draw. 

Step 1: Calculate the probability of drawing a Black card on the first draw. There are 26 Black cards in a deck of 52 cards. Therefore, the probability of drawing a Black card on the first draw is 26/52.

```
