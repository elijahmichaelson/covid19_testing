# covid19_testing

The UW Virology lab runs a good share of Washington States covid19 tests and they report their average patient positive rate, which is around 7.5% right now and fairly stable. https://twitter.com/uwvirology?lang=en

If a PCR test is run for every sample they recieve, which is the standard method of detecting presence of the corona virus, then the vast majority of results will be negative. However, if we ran a PCR test on _combined groupings_ of the samples, we will still obtain a negative result if all samples in that particular grouping do not contain the virus, and then we can rerun the individual samples in the positive groupings to identify which samples are positive. For low patient positivity rates, we can see drastic reductions in the _total number of PCR tests_ we must conduct by following this method.

A simulation is provided to determine a good grouping size.

![](https://github.com/elijahmichaelson/covid19_testing/blob/master/best_group_size.png)
