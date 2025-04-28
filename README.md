# cse-ce-isye524-homework-7--convex-programs-solved
**TO GET THIS SOLUTION VISIT:** [CSE-CE-ISyE524 Homework 7- Convex programs Solved](https://www.ankitcodinghub.com/product/cse-ce-isye524-homework-7-convex-programs-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;120330&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE-CE-ISyE524 Homework 7- Convex programs Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
1. Moving averages. There are many ways to model the relationship between an input sequence {u1,u2,…} and an output sequence {y1,y2,…}. In class, we saw the moving average (MA) model, where each output is approximated by a linear combination of the k most recent inputs:

MA: yt ≈ b1ut + b2ut−1 + ··· + bkut−k+1

We then used least-squares to find the coefficients b1,…,bk. What if we didn’t have access to the inputs at all, and we were asked to predict future y values based only on the previous y values? One way to do this is by using an autoregressive (AR) model, where each output is approximated by a linear combination of the ` most recent outputs (excluding the present one):

AR: yt ≈ a1yt−1 + a2yt−2 + ··· + a`yt−`

Of course, if the inputs contain pertinent information, we shouldn’t expect the AR method to outperform the MA method!

a) Using the same dataset from class uy_data.csv, plot the true y, and on the same axes, also plot the estimated ˆy using the MA model and the estimated ˆy using the AR model. Use k = 5 for both models. To quantify the difference between estimates, also compute ky − yˆk for both cases.

b) Yet another possible modeling choice is to combine both AR and MA. Unsurprisingly, this is called the autoregressive moving average (ARMA) model:

ARMA: yt ≈ a1yt−1 + a2yt−2 + ··· + a`yt−` + b1ut + b2ut−1 + ··· + bkut−k+1

Solve the problem once more, this time using an ARMA model with k = ` = 1. Plot y and ˆy as before, and also compute the error ky − yˆk.

Note: For the problems in this question you don’t need to use optimization codes; you can just use the “backslash” notation for solving linear least squares.

2. The Huber loss. In statistics, we frequently encounter data sets containing outliers, which are bad data points arising from experimental error or abnormally high noise. Consider for example the following data set consisting of 15 pairs (x,y).

x 1 2 3 4 5 6 7 8 9 10 11 12 13 14 15

y 6.31 3.78 24 1.71 2.99 4.53 2.11 3.88 4.67 4.25 2.06 23 1.58 2.17 0.02

The y values corresponding to x = 3 and x = 12 are outliers because they are far outside the expected range of values for the experiment.

a) Compute the best linear fit to the data using an `2 cost (least squares). In other words, we are looking for the a and b that minimize the expression:

`2 cost:

Repeat the linear fit computation but this time exclude the outliers from your data set. On a single plot, show the data points and both linear fits. Explain the difference between both fits.

b) It’s not always practical to remove outliers from the data manually, so we’ll investigate ways of automatically dealing with outliers by changing our cost function. Find the best linear fit again (including the outliers), but this time use the `1 cost function:

`1 cost:

Include a plot containing the data and the best `1 linear fit. Does the `1 cost handle outliers better or worse than least squares? Explain why.

c) Another approach is to use an `2 penalty for points that are close to the line but an `1 penalty for points that are far away. Specifically, we’ll use something called the Huber loss, defined as:

(x2 if − M ≤ x ≤ M

φ(x) =

2M|x| − M2 otherwise

Here, M is a parameter that determines where the quadratic function transitions to a linear function. The plot on the right shows what the Huber loss function looks like for M = 1.

The formula above is simple, but not in a form that is useful for us. As it turns out, we can evaluate the Huber loss function at any point x by solving the following convex QP instead:

 2  minimize w + 2Mv

 v,w  subject to: x| ≤ w + v



v ≥ 0, w ≤ M

Verify this fact by solving the above QP (with M = 1) for many values of x in the interval −3 ≤ x ≤ 3 and reproducing the plot above. Finally, find the best linear fit to our data using a Huber loss with M = 1 and produce a plot showing your fit. The cost function is:

Huber loss:

3. Heat pipe design. A heated fluid at temperature T (degrees above ambient temperature) flows in a pipe with fixed length and circular cross section with radius r. A layer of insulation, with thickness w, surrounds the pipe to reduce heat loss through the pipe walls (w is much smaller than r). The design variables in this problem are T, r, and w.

Now the problem: maximize the total heat flow down the pipe, subject to an upper limit Cmax on total cost, and the constraints

Tmin ≤ T ≤ Tmax, rmin ≤ r ≤ rmax wmin ≤ w ≤ wmax, w ≤ 0.1r

a) Express this problem as a geometric program, and convert it into a convex optimization problem.

b) Consider a simple instance of this problem, where Cmax = 500 and α1 = α2 = α3 = α4 = 1. Also assume for simplicity that each variable has a lower bound of zero and no upper bound. Solve this problem using JuMP. Use the Ipopt solver and the command @NLconstraint(…) to specify nonlinear constraints such as log-sum-exp functions. Have your code print the optimal values of T, r, and w, as well as the optimal objective value.
