

### Inference Example - Fair or Fixed Coin Flip

Suppose your friend offers a coin flip bet to you, but you know he has a fair and a fixed coin. The fair coin obviously has a .50 EV of Heads, but the fixed coin has a 0.70 EV of Heads. He lets you flip the coin 5 times to determine whether you think it's fair or fixed and you get 2 Heads and 3 Tails (n=5, x=2). Determine whether or not the coin if fair or fixed given this experiment.

Under the Bayesian framework, we can incorporate prior, subjective information. Suppose our friend has tried to trick you with a loaded coin in the past, so you have a predetermined idea that he might be doing it again here. With this new assumption, we can incorporate it into the inference by leveraging Bayes Theorem and applying a Prior that we think the coin has a 0.60 chance of being loaded (or 0.90 in the bottom example of the screenshot).  
![[Pasted image 20230610102636.png]]
![[Pasted image 20230612131710.png]]
![[Pasted image 20230612092910.png]]
![[Pasted image 20230612122329.png]]

Using the prior assumption in addition to the observed assumption, we can back out an actual probability indicating the confidence in our final prediction (unlike the Frequentist framework)


### Detailed Example Walkthrough
- Below is an exercise taken from class
- Note the progression of the problem
	- Establish Priors (subjective)
	- Determine distribution function
	- Set up likelihood function for initial conditional probabilities
	- Execute Bayes' Theorem using the Likelihood Functions and Priors

![[Pasted image 20230612155523.png]]


### Prior and Posterior Intervals

- Expressing confidence by creating a distribution of the value of theta
	- This allows us to express a probability confidence in the theta value
		- Something frequentist framework does not facilitate

- Highest Posterior Density (HPD)
	- 
![[Pasted image 20230621141029.png]]