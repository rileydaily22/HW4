# HW 4

Note this homework is a little shorter than it would normally be due to project 1. Most of the data visualization will be on project 1.

### 1. (ROS 2.7) 2 points

- a. Give an example of a scenario of measurements that have validity but not reliability.
- b. Give an example of a scenario of measurements that have reliability but not validity.


### 2. (ROS 3.3) 2 points

Using R, graph probability densities for the normal distribution, plotting several different curves corresponding to different choices of mean and standard deviation parameters.

### 3. (ROS 3.6) 4 points

A test is graded from 0 to 50, with an average score of 35 and a standard deviation of 10. For comparison to other tests, it would be convenient to rescale to a mean of 100 and a standard deviation of 15.

- a. Label the original test scores as $x$ and the rescaled scores as $y$, come up with a linear transformation ($y = ax _ b$) so that y has mean 100 and standard deviation 15.

- b. what is the range of possible values for $y$?

- c. Simulate 100 test scores for $x$ from a truncated normal distribution with mean 35 and standard deviation of 10 (hint: [https://cran.r-project.org/web/packages/TruncatedNormal/TruncatedNormal.pdf](https://cran.r-project.org/web/packages/TruncatedNormal/TruncatedNormal.pdf)). Then create a plot with $x$ and $y$. 
