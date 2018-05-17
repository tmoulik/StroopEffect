# StroopEffect
Project: Hypothesis testing for Stroop Effect.

More information on the stroop Effect can be found here:
https://faculty.washington.edu/chudler/words.html

And the stroop test can be taken here:
https://faculty.washington.edu/chudler/java/ready.html

The code is based on the data: stroopeffect.csv 

## Installation: 
To use this code, you would need to install Jupyter.

## Description:
The strooptest tests whether there is a time difference in correctly identifying the color while reading congruent vs. incongruent word.

The null hypothesis is that the time taken to say the color is independent of the type of word, i.e. there is no effect on the time given any type of word. Hence the difference in their times is <=0. The alternative hypothesis is that the time to taken to read incongruent words is greater.

    H0 : dt<=0
    H1 : dt>0 

where dt is the time differene between the two types. Here we are doing a one-sided hypothesis test. The null choice is typically when there is no effect and alternative is when there is some effect. I look at the t-test as the population standard deviation is not known and the sample size is very small, and I can reject the null hypothesis based on the t and p-value.

## Usage
Run the code stroopeffect in Jupyter. It reads the data present in the directory.
