# tony-award-prediction

Data and analysis for a FiveThirtyEight-style prediction of the 2019 Tony awards - musicals only! I built a clean dataset of various Broadway awards and how well they predicted winners in each category, and used it to weight the various nominees for 2019 after the run-up awards were announced. This was specifically inspired by [FiveThirtyEight's Oscar tracker by Walt Hickey](https://fivethirtyeight.com/features/how-our-oscars-tracker-works/).

[Notebook with the code and results](https://github.com/drsaunders/tony-award-prediction/blob/master/tony-award-prediction.ipynb)

I [publicly predicted](https://www.broadwayworld.com/board/readmessage.php?thread=1117325&boardname=st..):

* **Hadestown will win Best Original Musical**
* Kiss Me, Kate will win Best Revival
* **Rachel Chavkin will win Best Director**
* Tootsie will win Best Score
* **Santino Fontana will win Best Actor**
* **Stephanie J. Block will win Best Actress**
* **Andre De Shields will win Best Featured Actor**
* **Ali Stroker will win Best Featured Actress**

With actual wins in bold. That's 6 out of 8, when chance would be about 2 correct. It wasn't a particularly hard to predict year based on the chatter by experts, but I'm proud that my model didn't incorporate that information at all, and did quite well using purely wins and nominations.

I did this for fun, but after I posted on broadwayworld.com, an editor emailed me and said he'd love to feature it on the site next year. Of course next year was 2020, when all predictions are off. And my heart breaks for Broadway, its performers, creators, and crew  - and also for the $600 of Broadway tickets I had for shows in March 2020 (which would have including Patti Lupone singing Ladies who Lunch!) 

If things ever get back to "normal", I would improve the model by tuning the weights of nominations and wins with holdout data (predicting the future), and correct a significant source of bias: that shows already nominated during their off-Broadway runs by the Drama Desk awards are then ineligible when they come to Broadway, and their chances are much worse when they are off-Broadway shows relative to that year's Broadway shows.
