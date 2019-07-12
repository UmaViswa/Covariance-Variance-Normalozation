
Normalization constant:
The concept of a normalizing constant arises in probability theory and a variety of other areas of mathematics. The normalizing constant is used to reduce any probability function to a probability density function with total probability of one.

Covariance:
Covariance is one of the a family of statistical measures used to analyze the linear relationship between two variables.
The covariance of two variables (x and y) can be represented as cov(x,y). If E[x] is the expected value or mean of a sample ‘x’, then cov(x,y) can be represented in the following way:
cov(x,y)=E[(x-µx)(y-µy)]
        =E[xy]-E[x]E[y]
        =E[xy]-µxµy
    µxµy=E[x]&E[y] respectively

If we look at a single variable, say ‘y’, cov(y,y), the expression can be written in the following way:
cov(y,y)=var(y)=s^2(y) = s^2(y)
here, var is variance of variable
var(y) = E[(y-µy)^2]
also var(y)=s^2
where s^2 is sample variance

Now as we see, in the image above, ‘s²’ or sampled variance is basically the covariance of a variable with itself. This term can also be defined in the following manner:
For one variable
s^2 = cov(x,x)=sum(x-mean(x))^2/n-1
              =sum(x-mean(x)(x-mean(x)))/n-1

For two variable
cov(x,y)=sum(x-mean(x)(y-mean(y)))/n-1

In the above formula, the numerator of the equation(A) is called the sum of squared deviations. In equation(B) with two variables x and y, it is called the sum of cross products. In the above formula, n is the number of samples in the data set. The value (n-1) indicates the degrees of freedom.

To explain what degrees of freedom are, let us just take an example. In a set of 3 numbers with the mean as 10 and two out of three variables as 5 and 15, there is only one possibility of the value that the third number can take up i.e. 10. With any set of 3 numbers with the same mean, for example: 12,8 and 10 or say 9,10 and 11, there is only one value for any 2 given values in the set. You can basically change the two values here and the third value fixes itself. The degree of freedom here is 2. Essentially, degrees of freedom is the number of independent data points that went into calculating the estimate. As we see in the example above, it is not necessarily equal to the number of items in the sample (n).

The  diagonal of a covariance matrix provides the variance of each individual variable, covariance itself.

Variance:

Variance (σ2) is a measurement of the spread between numbers in a data set. It measures how far each number in the set is from the mean and is calculated by taking the differences between each number in the set and the mean, squaring the differences (to make them positive) and dividing the sum of the squares by the number of values in the set.Variance measures the variation of a single random variable.       
 Var(x) = (1/(n-1))sum(x(i) - mean(x)) * 2      
   where n = samples

   i = some arbitary number

 the value of x varies from i to n.A variance value of zero indicates that all values within a set of numbers are identical; all variances that are non-zero will be positive numbers. A large variance indicates that numbers in the set are far from the mean and each other, while a small variance indicates the opposite.
