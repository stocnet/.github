## Welcome 👋

*stocnet* is an open software system for the advanced statistical analysis of social networks.
Its history reaches [back to 1998](https://stocnet.gmw.rug.nl/content/project.htm),
but its new guise as a github organisation is since the start of 2024.
It currently includes the following software:

- [manynet](https://github.com/stocnet/manynet) provides many fundamental tools for working with many (if not most) types, formats, and classes of networks. These include functions for _making_ networks (e.g. importing existing data, generating various random graphs), _modifying_ networks (e.g. reformatting, transforming, splitting, and joining), to easy _mapping_ for visualising graphs with sensible and flexible default individually, comparatively, and dynamically.
- [migraph](https://github.com/stocnet/migraph) builds on `{manynet}` to enable network analysis and modelling of multimodal, multilevel, and multilayer networks. It includes a range of measures that all work for one- and two-mode networks, their nodes and ties, algorithms for identifying motifs and community or equivalence memberships in them, and modelling one- and two-mode networks with multiple regression quadratic assignment procedure (MRQAP).
- [goldfish](https://github.com/stocnet/goldfish) offers tools for applying statistical models to network/relational event data, time-stamped sequences of interactions or affiliations between actors or entities within a network. In addition to relational event models (REMs), the package includes rate, choice, and coordination processes for one- and two-mode dynamic network actor models (DyNAMs) and dynamic network actor models for interactions (DyNAMi).
- [rsiena](https://github.com/stocnet/rsiena) performs simulation-based estimation of Stochastic Actor-oriented Models (SAOMs) for longitudinal network data collected as panel data (repeated observations of social networks on the same node set - minor changes of the node set are allowed). Dependent variables can be single or multivariate networks, which can be directed, non-directed, or two-mode; these can be combined with actor variables, which then leads to a "networks and behavior" study.
- [MoNAn](https://github.com/stocnet/MoNAn) implements the method to analyse weighted mobility networks or distribution networks as outlined in: [Block et al (2022)](https://www.sciencedirect.com/science/article/abs/pii/S0378873321000654). The purpose of the model is to analyse the structure of mobility, incorporating exogenous predictors pertaining to individuals and locations known from classical mobility analyses, as well as modelling emergent mobility patterns akin to structural patterns known from the statistical analysis of social networks.
- [ERPM](https://github.com/stocnet/ERPM) extends exponential random graph models (ERGMs) for partitions, i.e. sets of non-overlapping groups, such as face-to-face interactions, animal herds, political coalitions, etc. This model can be used to explain cross-sectional or longitudinal observed partitions through group formation processes based on individual attributes, relations between individuals, and size-related factors.

## 👩‍💻 Useful resources

- manynet/migraph
  - [manynet/migraph tutorials](https://github.com/stocnet/manynet?tab=readme-ov-file#tutorials)
- RSiena
  - [Oxford RSiena website](https://www.stats.ox.ac.uk/~snijders/siena/)
  - [Latest RSiena manual](https://www.stats.ox.ac.uk/~snijders/siena/RSiena_Manual.pdf)
  - [RSiena groups.io mailing list](https://groups.io/g/RSiena)
- goldfish
  - [goldfish vignettes](https://github.com/stocnet/goldfish?tab=readme-ov-file#vignettes)
- MoNAn
  - [Latest MoNAn manual](https://osf.io/preprints/socarxiv/8q2xu)
  - [MoNAn basic tutorial](https://github.com/stocnet/MoNAn?tab=readme-ov-file#readme)

## 🙋‍♀️ Upcoming workshops

- 20-24 January 2025: *15th Winter School on Longitudinal Social
Network Analysis* that will take place at the *University of Groningen*
(The Netherlands) in the week of *20-24 January 2025*. This consists of a three-day introductory course followed by
a two-day *Advanced Siena Users' Meeting (AdSUM-2025)* that includes a
Master Class opportunity for in-depth consultation related to your data
sets and/or work-in-progress. Teachers will be *Christian Steglich* and *Tom Snijders*.
See  https://steglich.gmw.rug.nl/workshops/Groningen2025-call.htm
- 18-20 February 2025: Online livestream workshop *Introduction to longitudinal social network analysis using RSiena*.
See https://instats.org/seminar/longitudinal-social-network-analysis2. Teacher will be *Tom Snijders*.
## :information_desk_person: Contributions

We welcome contributions to any of these packages.
Contributions might take the form of raising issues (bugs or features), discussing different options,
or proposing changes to the codebase.
We have reserved a space for discussions across the stocnet packages at the [Discussions](https://github.com/orgs/stocnet/discussions) tab above.
