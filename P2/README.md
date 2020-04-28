# Predicting the 2012 US Presidential Elections

The project employs different techniques in order to make predictions and also involves discussion on the various biases which may be involved. Firstly, data is used from Predictwise. Predictwise did aggregate polling data and estimated the win probabilities of Obama and Romney for each of the states. The result is computed by performing 10000 simulations on the data and the results are plotted and analysed consequently.

Then an attempt is made to estimate the probability of each of the candidate winning in a particular state depending on the poll created by Gallup. The estimation of probabilities is carried out by different models of increasing complexities accounting the uncertainities and the biases. The results are analysed in each of the scenario.

Until now all the models used only employed partisan affiliation, as the basis of forecast but now a new feature the Partisan Voting Index (PVI) is introduced and also used for making the predictions. In order to compute the probabilities, Logistic Regression was used and after obtaining the probabilities, the results were analysed by simulations. 

During the analysis of election polls, an individual would have to take care about the following uncertainities and biases:

- One needs to carry out hypothesis testing in order to validate the model. Increasing the number of tests made would correspond to increased confidence in the model.
- One needs to also incorporate the sampling error as getting the complete population isn't feasible.
- The following biases need to be taken in consideration while using the polls:
    1. One should ensure that the people who have been interviewed are representative of the sample who actually vote.
    2. It also might be the case that there are individuals who claim to favor a certain party but are significantly influenced by others.
    3. The polls need to be weighted by their recency, as the polls which are done just before the elections are more accurate than the ones which were done a month or two ago.
- Biases can significantly change the results and one needs to caliberate the models for them. A particular way of model caliberation is by using the current model for the past elections and then observing whether there is any bias or not. However, this approach is empirical.
- It is better to use more features rather than just partisan affiliation.
- Aggregating the polls of several polsters would average out the biases and thus we would get estimates which are free from bias. Also one should not consider all the polls equal and also weight them individually as well.
