## Definitions: 

* ANOVA model, observational study, experiment, confounding factor, randomized controlled trial
* placebo
* double-blind study
* factor and level
* effect, balance in an ANOVA model
* randomized complete block design
* balanced incomplete block design (balance, adjusted means, ANOVA table)
* the 1-way ANOVA layout (definition, means model, effects model, fixed effects, random effects, ANOVA table, balance, Gaussian assumptions)
* 2-way ANOVA layout for blocks (definition, means and effects models, balance, ANOVA decomposition, ANOVA table)
* factor coding, pooled estimate of variance
* nominal Type I error
* family-wise Type I error rate.

## Concepts and Basic Results:
Any reference to ANOVA models includes both one-way and two-way lay-
outs, the latter including additive terms unless otherwise noted. Thus,
when you are asked to know how to justify degrees of freedom in ANOVA
tables, you should consider df for both the one-way and two-way layouts.

* We had three different uses of the word control ... what are they?
* Confounding variable; how to adjust or control for a confounding
  variable?
* Stochastic consequences of randomized experiment. For example, in the case of
  randomly assigning two treatments (A and B or T reatment and Control) to a
  sample of subjects we discussed $$Var(\bar{X} - \bar{Y})$$.  Randomization
  leads to dependence in (a) the draws $$x_1, \ldots, x_n$$ and $$y_1, \ldots,
  x_m$$, and (b) $$\bar{X}$$ and $$\bar{X}$$. Be sure you are able to explain
  why the usual formula, $$Var( \bar{X} - \bar{Y} ) = \frac{\sigma^2}{n} +
  \frac{\tau^2}{m}$$, which assumes two iid samples, remains useful in this
  scenario.
* Logic of a randomization test.
* In the context of experimental design, what is blocking and what is
  its purpose? Be prepared to give an example of a blocked design.
* Estimable parameters in BIBDs.
* What is an analysis of variance and what does it tell us?
* Logic of F-tests in ANOVA layouts.
* Role of parameter constraints in ANOVA models (e.g. zero-sum con-
  straint).
* Know how to justify degrees of freedom in ANOVA tables/models.
* Know the regression version of ANOVA models; be sure you un-
  derstand the issue of parameterizing categorical variables and the
  corresponding interpretation of regression coefficient estimates.
* Know how to read and interpret R output from ANOVA models,
  both the ANOVA table output and the regression output. Be able to confirm all
  R output associated with ANOVA tables and regression parameter estimates (via
  lm).
* Idea of multiple comparisons and its relation to the familywise error rate.
* Bonferroni and Tukey methods for multiple comparisons.
