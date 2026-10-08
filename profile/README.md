## Welcome 👋

*stocnet* is an open software system for the advanced statistical analysis of social networks.
Its history reaches [back to 1998](https://stocnet.gmw.rug.nl/content/project.htm),
but its new guise as a github organisation is since the start of 2024.
It currently includes the following software:

- [manynet](https://github.com/stocnet/manynet) provides many fundamental tools for working with many (if not most) types, formats, and classes of networks. These include functions for _making_ networks (e.g. importing existing data, generating various random graphs) and _modifying_ networks (e.g. reformatting, transforming, splitting, and joining).
- [netrics](https://github.com/stocnet/netrics) lends tools for analysing networks, through _marks_, _measures_, _memberships_, and _motifs_ for networks, nodes, and ties in many (if not most) types, formats, and classes of networks.
- [migraph](https://github.com/stocnet/migraph) builds on `{manynet}` to enable network analysis and modelling of multimodal, multilevel, and multilayer networks. It includes a range of measures that all work for one- and two-mode networks, their nodes and ties, algorithms for identifying motifs and community or equivalence memberships in them, and modelling one- and two-mode networks with multiple regression quadratic assignment procedure (MRQAP).
- [goldfish](https://github.com/stocnet/goldfish) offers tools for applying statistical models to network/relational event data, time-stamped sequences of interactions or affiliations between actors or entities within a network. In addition to relational event models (REMs), the package includes rate, choice, and coordination processes for one- and two-mode dynamic network actor models (DyNAMs) and dynamic network actor models for interactions (DyNAMi).
- [rsiena](https://github.com/stocnet/rsiena) performs simulation-based estimation of Stochastic Actor-oriented Models (SAOMs) for longitudinal network data collected as panel data (repeated observations of social networks on the same node set - minor changes of the node set are allowed). Dependent variables can be single or multivariate networks, which can be directed, non-directed, or two-mode; these can be combined with actor variables, which then leads to a "networks and behavior" study.
- [MoNAn](https://github.com/stocnet/MoNAn) implements the method to analyse weighted mobility networks or distribution networks as outlined in: [Block et al (2022)](https://www.sciencedirect.com/science/article/abs/pii/S0378873321000654). The purpose of the model is to analyse the structure of mobility, incorporating exogenous predictors pertaining to individuals and locations known from classical mobility analyses, as well as modelling emergent mobility patterns akin to structural patterns known from the statistical analysis of social networks.
- [ERPM](https://github.com/stocnet/ERPM) is an exponential family model for partitions, akin to the exponential random graph model (ERGM) for networks. Partitions are sets of non-overlapping groups, such as face-to-face interactions, animal herds, political coalitions, etc. This model can be used to explain cross-sectional or longitudinal observed partitions through group formation processes based on individual attributes, relations between individuals, and size-related factors.
- [autograph](https://github.com/stocnet/autograph) offers ggplot2-based plotting methods for all of the above packages. The package also includes sensible defaults and consistent theming.

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

- 3-10 September 2026: five half-day workshops *Introduction to Social Network Analysis* at the 2026 European Consortium for Political Research conference online and in Krakow. Registration is now open [here](https://ecpr.eu/Events/Event/PanelDetails/15556). Teacher will be *James Hollway*.
- 18-22 January 2027: The *16th Winter School on Longitudinal Social Network Analysis* and the *Advanced Siena Users' Meeting (AdSUM-2027)* will take place in Groningen, The Netherlands. Registration is open via the [Winter School's website](https://steglich.gmw.rug.nl/workshops/Groningen2027-call.html). Teachers will be *Christian Steglich* and *Tom Snijders*.
- Instats offers an introductory online workshop about the Stochastic Actor-oriented Model and the RSiena package, taught by Tom Snijders. It is an on-demand workshop, which you can follow at your own time and at your own pace. It consists of 18 recorded sessions of 45 minutes each.
The course is at https://instats.org/seminar/longitudinal-social-network-analysis.


## :information_desk_person: Contributions

We welcome contributions to any of these packages.
Contributions might take the form of raising issues (bugs or features), discussing different options,
or proposing changes to the codebase.
We have reserved a space for discussions across the stocnet packages at the [Discussions](https://github.com/orgs/stocnet/discussions) tab above.
