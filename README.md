# Election Methods

Examples of Voting Methods and Tabulation, in both python and notebook format.

**New!** [Live Jupyter Editor of the repository](https://electionscience.github.io/examples/lab/index.html)

## Election Data

This is the home of the Center for Election Science's universal election dataset. 

Election data is stored in .csv format and compiled into a SQLite DB for hosting on Datasette. 

To update the Datasette instance on data.electionscience.org, run `datasette publish cloudrun ./elections.db --service=elections --install=datasette-vega` with the appropriate permissions. Contact @fsargent for more information.

## Voting Methods

When single winner methods are equivalent to a multi winner method with one seat, the single winner method is not included for simplicity. For example, Approval Voting and Sequential Proportional Approval Voting yield the same first winner with the same methodology, so Approval Voting is not included as a separate example.

### Rated Methods

- [Sequential Proportional Approval Voting](https://en.wikipedia.org/wiki/Sequential_proportional_approval_voting) (SPAV)
- [Method of Equal Shares](https://en.wikipedia.org/wiki/Method_of_Equal_Shares) (MES)
- [STAR-PR](https://electowiki.org/wiki/Allocated_Score)

### Ranked Methods

- [Single Transferable Vote](https://en.wikipedia.org/wiki/Single_transferable_vote) (AKA STV, Proportional IRV, Propotional RCV, Proportional Hare)

## Contributions

Please include both a python version and a notebook version. Notebooks should have completed results so they can be viewed in Github without execution.
PRs are welcome.

## Papers

Some recommended reading for those wanting to contribute to the repo:

- [Proportional Representation in Elections: STV vs PAV](https://www.ifaamas.org/Proceedings/aamas2019/pdfs/p1946.pdf)
- [Multi-Winner Voting with Approval Preferences](https://arxiv.org/pdf/2007.01795.pdf)
- [Proportional Justiﬁed Representation](https://ojs.aaai.org/index.php/AAAI/article/download/10611/10470)
- [Proportionality and the Limits of Welfarism](https://arxiv.org/abs/1911.11747)

## Great Examples

- [VotingVisualizer](https://www.chocolatepi.net/voteapp/)
- [Guide to a Better Ballot](https://ncase.me/ballot/)
- [Smart Voting Simulator](https://www.howtofixtheelection.com/ballot/)
- [A Python library of approval-based committee (ABC) rules](https://github.com/martinlackner/abcvoting)
