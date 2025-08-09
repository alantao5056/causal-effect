# Causal Effect

The question is: What is the average treatment effect, of exposing people to Spanish-speakers, on their attitudes toward immigration? I have loaded the data, considered validity, stability, representativeness, and unconfoundedness. One problem is that politics might have changed throughout this time. I then made bayesian regression model of the end attitude to the treatment. I used add epred draws and subtracted the control from the treatment to get the causal effect. I then plotted a histogram of the causal effect

Check out the full paper here: [https://rpubs.com/alienjao/causal](https://rpubs.com/alienjao/causal)
