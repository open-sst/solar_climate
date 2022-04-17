# How to write a paper proving there's a link between the sun and climate

The following methodology, is a useful guide to getting started in this exciting field. You just have to look at the sun (not recommended) to know it plays an important role in the climate.

1. Collect as many different solar indices as possible.
2. Collect as many climate time series as possible (if you can get gridded data, that's even better).
3. You don't have enough series so also calculate cumulative sums, and first differences of all these series.
4. Calculate correlations between all possible pairs.
5. If correlations are significant (it doesn't matter how you calculate this, but whatever standard test is available in your stats software is probably fine<sup>1</sup>), go to step X. If there's more than one, pick the highest.
6. If none of the correlations are significant then smooth the series (there are lots of ways to smooth a series, so try a few different combinations<sup>2</sup>.) and recalculate the correlations.
7. If correlations are significant, go to step X.
8. If none of the correlations are significant even after smoothing, try changing the lag for each series and hunt for the lags that give the highest correlations.
9. If correlations are significant, go to step X
10. If none of the correlations are significant, then perhaps certain parts of the solar cycle "trigger" an event. Hunt through all the series for coincident "events" e.g. the peak of the solar cycle and a transition of the NAO.
11. If you don't have a significant correlation or relationship at this point, you haven't been trying hard enough. You have two options: (a) go back to step 1 and think harder (you got this) or (b) look at the existing literature for inspiration. There's another option (c) which is to recast the paper as exploratory and then nothing needs to be significant. Insignificant correlations can still be high enough to be "suggestive" and "something to keep an eye on as more data come in".
12. It might be that, even now, the relationship isn't as good as it could be. If you have followed the above steps faithfully, then the problem is probably bad data. Luckily data is always bad<sup>3</sup> when it gets in the way of a sun-climate relationship so you don't have to get into details. If you can get hold of some unadjusted data, try that too.
13. If the data aren't bad (though they probably are), it's possible that mainstream climate scientists are a teeny-tiny bit right. If you're missing a bit of warming, then it could be that greenhouse gases are playing a very minor role.
14. Start writing the paper. Emphasise how big and hot the sun is. Cite every single paper ever written on the subject. Cited papers don't have to agree with your analysis. It doesn't even matter if it contradicts it; sometimes a relationship will flip sign. Don't fall into the trap some do of thinking that it's necessary to have a physical mechanism for the relationship. Remember: the relationship you have found is *highly-signficant* so there *must* be a physical mechanism even if it isn't immediately apparent, violates causality or may involve inconvenient elves. The physical mechanism will be a puzzle for future, grateful generations to solve. Speculation is allowed, but by no means necessary.
15. Some reviewers may point out that correlation is not causation. They don't know what significant means, the chumps. 
16. In fact, you should expect a rough ride through the review process. You should aim high - Nature or Science - for an initial submission because this is important work that challenges the green nonsense spouted by climate activists, but don't be disheartened if it's desk-rejected. You may have to submit several times before you find an editor with the guts to publish it.

<sup>1</sup> Significance is important. Your results have to be significant. If your stats package is indicating that an obviously interesting relationship is insignificant, it's probably because the assumptions it makes are wrong. In these situations, you're better off doing a "monte carlo" estimate of significance. Remember the null hypothesis is one in which the probability of your signal is very low.

<sup>2</sup> Smoothing series is an art. You want to choose a filter that emphasises the key frequencies in your data. A good way to find these is to do a fourier transform or wavelet decomposition of the data, or some kind of non-linear decomposition. Pick out the most prominent frequency then choose a moving average filter with a frequency response that emphasises that particular frequency. This is OK because you really want to isolate your signal. To be doubly sure, you might want to use both low and high pass filters to really screen out everything but.

<sup>3</sup> Bad data can be due to many things: urbanisation, station siting, poorly maintained equipment, change in equipment, station moves, because you have a hunch its bad. It can also be due to corrections for some or all of these factors.
