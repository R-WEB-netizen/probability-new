1. Write a Python program to simulate the following scenarios:  
    a. Tossing a coin 10,000 times and calculating the experimental probability of heads and tails.

   step 1. import random ( its describe the library random )
   step 2. tosses = 10000 (tossing a coin 10,000 time )
   step 3. I take two two variable number heads and tails.
   step 4.  I write the condition to toss coin
                   for i in range(tosses):----this line integer(i) number  in range between 10,000  under  The loop runs 10,000 times to simulates the coin tosses.
                   result = random.choice(["Heads", "Tails"])  ----- randomly selects either "Heads" or "Tails".
   step 5. heads / tosses gives the experimental probability of heads.
   step 6. tails / tosses gives the experimental probability of tails.

   step 7. display results.
   step 8. Since the coin is fair, the probabilities should be close to:

           Heads ≈ 0.5
           Tails ≈ 0.5


b. Rolling two dice and computing the probability of getting a sum of 7. Steps
a. Use Python's random module for simulations. 
b. Implement loops for repeated trials.
c. Track outcomes and compute probabilities.


step 1. import random (its describe the library imports the random module).
step 2. we take number of trials is 10,000 
step 3. sum of 7 in code  sum_of_7. (its variable we take to find sum)
step 4. we write the statement in for loop (roll two dice repeatedly )
step 5. we calculate the probability 
step 6. then show thw display results.
   Total Trials: 10000
Number of times sum = 7: 1692
Experimental Probability of getting sum 7: 0.1692


2. Write a function to estimate the probability of getting at least one "6" in 10 rolls of a fair die.  
  Steps  
      a. Simulate rolling a die 10 times using a loop.  
      b. Track trials where at least one "6" occurs.  
      c. Calculate the proportion of successful trials.
   

step 1. import random (its describe the library imports the random module)
step 2. we write the function to estimate probability .
step 3. in the function  i write the statement  to repeat the experiment.
step 4.  in statement i write the roll the dice 10 times.
step 5.   and then count successful trials.
step 6. now , calculate the probabilty of success trials.
step 7. number of experiment is 10,000.
step 8. estimate the probability of number.
Total Trials: 10000
Estimated Probability of getting at least one 6 in 10 rolls: 0.8394



Conditional Probability and Bayes' Theorem


3. A bag contains 5 red, 7 green, and 8 blue balls. A ball is drawn randomly,
   its color noted, and it is put back into the bag. If this process is repeated 1000 times,
   write a Python program to estimate:  
     a. The probability of drawing a red ball given that the previous ball was blue.  
     b. Verify Bayes' theorem with the simulation results.  


Steps  
    a. Use random sampling to simulate the process.  
    b. Compute conditional probabilities directly from the data.  


    step 1. import the random library
    step 2. number of draws is 1000.
    step 3. first draw. 
    step 4. counters
    step 5. simulate draws.
    step 6. probability
    step 7. using Bayes' theorem.
    step 8. Display results

    output --- P(Red | Previous Blue) = 0.2872340425531915
               Bayes Theorem Result   = 0.2632978723404255

               
Random Variables and Discrete Probability
4. Generate a sample of size 1000 from a discrete random variable with the following distribution:  
  - P(X=1) = 0.25  
  - P(X=2) = 0.35  
  - P(X=3) = 0.4  
  Compute the empirical mean, variance, and standard deviation of the sample.  
  Steps  
      a. Use numpy.random.choice() to generate the sample.  
      b. Use numpy methods to calculate mean, variance, and standard deviation.

    
step 1. possible values of X.
step 2. corresponding probabilites.
step 3. generate a sample of size 1000.
step 4. calculate statistics.
step 5. display results.

   Sample Size: 1000
   Empirical Mean: 2.146
   Empirical Variance: 0.614684
   Empirical Standard Deviation: 0.784017856939496




Continuous Random Variables

5. Simulate 2000 random samples from an exponential distribution with a mean of 5. Visualize the distribution using:  
  a. A histogram.  
  b. A probability density function (PDF) overlay.  
  Steps  
      a. Use numpy.random.exponential().  
      b. Use matplotlib to create visualizations.

   step 1. mean of exponential distribution.
   step 2. generates 2000 random sample.
   step 3. create x values for the PDF.
   step 4. Exponential PDF.
   step 5. plot histogram.
   step 6. plot PDF.
   step 7. Add title and labels.
   step 8. show the plot.

<img width="585" height="453" alt="image" src="https://github.com/user-attachments/assets/1f975d0d-15c4-4e41-94a0-ebe586eb69df" />

Central Limit Theorem


6. Simulate the Central Limit Theorem by following these steps  
  a. Generate 10,000 random numbers from a uniform distribution.  
  b. Draw 1000 samples of size n = 30.  
  c. Calculate and visualize the distribution of sample means.  
  Steps  
      a. Use numpy.random.uniform().  
      b. Plot both the uniform distribution and the sample mean distribution for comparison.


step 1. generate 10,000 random numbers from a uniform distribution.
step 2. Draw 1000 samples of size 30 and calculate sample means
step 3. create the plots.
step 4. Uniform distribution.
step 5. distributin of sample means.
step 6. <img width="1189" height="490" alt="image" src="https://github.com/user-attachments/assets/b8e62bef-8913-4841-a98b-63be52ae7107" />

