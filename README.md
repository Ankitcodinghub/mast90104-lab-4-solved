# mast90104-lab-4-solved
**TO GET THIS SOLUTION VISIT:** [MAST90104 Lab 4 Solved](https://www.ankitcodinghub.com/product/mast90104-a-first-course-in-statistical-learning-solved-4/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;112911&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;MAST90104 Lab 4 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
1. Suppose that X is a random variable with density function,f, given by

where p(0),p(1),··· is a discrete probability mass function on {0,1,···} and each g(x;i) is a probability density function. Suppose that µ(i),σ2(i),M(t;i) are the mean, variance and moment generating function for the density g(x;i). Let M(t) be the moment generating function of X. Suppose also that N is a random variable with probability mass function p(i),i = 0,1,···. Show that

(a) E(X) = E(µ(N))

(b) var (X) = E(σ2(N)) + var (µ(N)) (c) M(t) = E(M(t;N)).

and

are independent. (Hint: Express them as a random “vector” and quadratic form respectively.)

3. An online survey collects data on factors that affect a person’s pay rate (per hour). The table below shows pay rate (pay) and number of years of education (yrEdu) of five participants.

id pay

yrEdu

1 7.06 9

2 18.93 12

3 20.17 12

4 29.58 16

5 33.90 20

(a) Let xi and yi denote the years of education and pay rate of individual i. We want to fit the model . Given that Pi x2i = 1025, ¯x = 13.8, ¯y = 21.928, Pi xiyi = 1684.02, find the least squares estimates of β0,β1

(b) Suppose we have calculate the least squares estimators b0 and b1 in R. Consider the following

R commands and output

&gt; pay = c(7.06,18.93,20.17,29.58,33.9)

&gt; yrEdu = c(9,12,12,16,20)

&gt; e = pay – (b0 + b1*yrEdu) &gt; t(e)%*%e

[,1]

[1,] 33.41216

Calculate the sample variance s2.

(c) Estimate the pay rate of a person with 14 years of education.

(d) The leverage of the data points are given as

&gt; model1_leverage

[1] 0.5164835 0.2445055 0.2445055 0.2664835 0.7280220 Calculate the standardised residual for the 3rd observation.

Practical exercises

Read Sections 5.1–5.3 of spuRs (which is available electronically in the library), then attempt the exercises below.

1. Last week you wrote a program to calculate h(x,n), the sum of a finite geometric series. Turn this program into a function that takes two arguments, x and n, and returns h(x,n).

Make sure you deal with the case x = 1.

2. Consider the following program

# Program spuRs/resources/scripts/err.r

# clear the workspace rm(list=ls())

random.sum &lt;- function(n) { # sum of n random numbers x[1:n] &lt;- ceiling(10*runif(n)) cat(“x:”, x[1:n], ” “) return(sum(x)) }

Below are the output of the function for n = 10 and n = 5

&gt; x &lt;- rep(100, 10)

&gt; show(random.sum(10))

x: 6 10 7 5 8 6 5 10 9 4

[1] 70

&gt; show(random.sum(5)) x: 8 9 4 5 10

[1] 536

Explain what is going wrong and how you would fix it.

3. In this question we simulate the rolling of a die. To do this we use the function runif(1), which returns a ‘random’ number in the range (0,1). To get a random integer in the range {1,2,3,4,5,6}, we use ceiling(6*runif(1)), or if you prefer, sample(1:6,size=1) will do the same job.

(a) Suppose that you are playing the gambling game of the Chevalier de M´er´e. That is, you arebetting that you get at least one six in four throws of a die. Write a program that simulates one round of this game and prints out whether you win or lose.

Check that your program can produce a different result each time you run it.

(b) Turn the program that you wrote in part (a) into a function sixes, which returns TRUE if you obtain at least one six in n rolls of a fair die, and returns FALSE otherwise. That is, the argument is the number of rolls n, and the value returned is TRUE if you get at least one six and FALSE otherwise.

How would you give n the default value of 4?

(c) Now write a program that uses your function sixes from part (b), to simulate N plays of the game (each time you bet that you get at least one six in n rolls of a fair die). Your program should then determine the proportion of times you win the bet. This proportion is an estimate of the probability of getting at least one six in n rolls of a fair die.

Run the program for n = 4 and N = 100, 1000, and 10000, conducting several runs for each N value. How does the variability of your results depend on N?

The probability of getting no 6’s in n rolls of a fair die is (5/6)n, so the probability of getting at least one is 1 − (5/6)n. Modify your program so that it calculates the theoretical probability as well as the simulation estimate and prints the difference between them. How does the accuracy of your results depend on N?

(d) In part (c), instead of processing the simulated runs as we go, suppose we first store the resultsof every game in a file, then later postprocess the results. You should read spuRs Chapter 4 to see how to read and write text files.

Write a program to write the result of all N runs to a textfile sixes_sim.txt, with the result of each run on a separate line. For example, the first few lines of the textfile could look like

TRUE

FALSE

FALSE TRUE FALSE

. .

Now write another program to read the textfile sixes_sim.txt and again determine the proportion of bets won.

This method of saving simulation results to a file is particularly important when each simulation takes a very long time (hours or days), in which case it is good to have a record of your results in case of a system crash.

4. Let y be a normal random vector with mean and variance

µ .

Let

.

.

From Theorem 3.8 we know that yTAy follows a χ2 distribution with degree of freedom 1 and noncentrality parameter λ = 4.5.

(a) Generate n = 1000 samples {y(1),…,y(n)} from MV N(µ,V ).

(b) Compute yTAy for all y(i) that we generated in part (a).

(c) Plot the histogram of the yTAy values that we have computed.

(d) Now generate n samples from distribution using rchisq().

(e) Plot the histogram of the generated samples on the same graph with the histogram in part

(c).
