# Hypothesis Testing

Commonly we wish to verify a hypothesis based on data we've collected.  Often
we perform comparisons between two distribution's parameters, such as compare
means.  The general flow of hypothesis testing involves:
1. Making initial assumption
2. Collecting data
3. Based on the data, or some statistic generated from the data, deciding
   whether or not to reject the initial assumption.

## Example: Is normal body temperature really 98.6 degrees F?

Consider the population of many, many adults. A researcher hypothesized that
the average adult body temperature is lower than the often-advertised 98.6
degrees F. That is, the researcher wants an answer to the question: "Is the
average adult body temperature 98.6 degrees? Or is it lower?" To answer his
research question, the researcher starts by assuming that the average adult
body temperature was 98.6 degrees F.

Then, the researcher went out and tried to find evidence that refutes his
initial assumption. In doing so, he selects a random sample of 130 adults. The
average body temperature of the 130 sampled adults is 98.25 degrees.

Then, the researcher uses the data he collected to make a decision about his
initial assumption. Namely, the researcher would like to know that **given 
the average body temperature is 98.6**, is a sample measurement of 98.25 likely 
or unlikely?

If it is likely, then the researcher does not reject his initial assumption
that the average adult body temperature is 98.6 degrees. **There is not enough
evidence to do otherwise.**

If it is unlikely, then:  
* either the researcher's initial assumption is correct and he experienced a very unusual event
* or the researcher's initial assumption is incorrect.

## Glossary

* Type I Error: the incorrect rejection of a true null hypothesis
* Type II Error: incorrectly failing to reject a false null hypothesis
* p-value: probability of a Type I error given our data
