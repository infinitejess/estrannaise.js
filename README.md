# estrannaise.js
estrannaise.js is a small playground for estradiol pharmacokinetics. It can simulate estradiol blood levels under arbitrary dosing regimes and schedules. In the near future it will allow users to infer model parameters from outside sources, including their personal blood levels.

Under the hood, estrannaise.js uses pharmacokinetic compartments models together with MCMC inference using either a flat Gaussian model or our very own homebrewed hierarchical Bayesian amodel called Emix.

**estrannaise.js is 100% client side, the data you enter or import never leaves your browser and is never transmitted to me or any other third-party**

# TODO
- Double click add to guess values of next row (same dose, next time from two last times)
- Add emix model of interstudy variability
- Handle mixed days/dates. When one or more dates Assume days are offsets from earliest date
- Enable/disable individual doses, if disabled then u visibility checkbox is disabled as well.
- Figure out the behavior when deleting first multi-dose row. Previous item should automatically take care of it.
- Add sublingual/buccal model (2C model?)
- Add patch model (3C model followed by glued 2C model if removal time specified)
- Add oral model (4C compartment with combined E1+E1S C's, or 5C with separate E1 and E1S C's)

# Disclaimer
This page, serving as a playground for estradiol pharmacokinetics, provides a simulation for
informational and entertainment purposes only. The developer(s) cannot guarantee the accuracy of the
predictions generated by the simulator. Users acknowledge that the software is offered "as is," without
any warranties.
The developer(s) assume no liability for direct or indirect damages resulting from the use of the simulator.
Users are strongly advised to exercise caution and seek professional medical advice for health-related queries.
