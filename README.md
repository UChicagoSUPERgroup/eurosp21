# SoK: Context Sensing for Access Control in the Adversarial Home IoT - Supplement Evaluation Table

This repository links to [the online version of the evaluation table (Tables 2-3)](https://docs.google.com/spreadsheets/d/1tcAb3B0-iyIoBK8ioKDfu4XtHkmp4Rwaf8RuKfn0OoY/edit?usp=sharing) in our paper, `SoK: Context Sensing for Access Control in the Adversarial Home IoT` (paper link).

## Goal

We provide the online version of our evaluation for our evaluation for several sensing methods (Tables 2-3 in the paper) as well as this repository for the following reasons:

1. The online table allows us to provide more details behind our reasoning for each score in our evaluation. This was not possible in the paper due to the conference page limit.
2. As we acknowledge in the paper, some scores were based on the teams' own judgement which could be subjective. This repository enables members of the security and sensing research communities to debate any evaluations they disagree with.
3. In the future, there will likely be more sensing methods relevant to contextual access control than the ones we included in the paper. It is also possible that some relevant sensing methods have escaped the team's literature review. With this repository, we and other researchers can update it with relevant sensing methods as they come up.

By making Tables 2-3 available in online and linked to this repository, we hope the community can help advance the state of knowledge regarding smart home sensors that enable contextual access control. 

## Questions / Suggestions / Requests of Revision

If you have a question, suggestion, or disagreement about our evaluations, please create an **Issue** to this repository using the following format:

```
Paper / Product - Criteria:
[The paper / product - criteria pair you would like to discuss (e.g. Google Voice Match - Replay Attack). You can put multiple pairs here if discussing multiple scores.]

Cell ID (Optional):
[The cell id(s) of the score(s) you would like to discuss, e.g. e.g., H6. This helps us locate the scores.]

Questions / Suggestions / Requests of Revision:
[State your questions, suggestions, or requests of revision. ]

References:
[Please include any references that you believe to be helpful for the discussion.]
```

Once we see the issue, we will be happy to open any related discussions until everyone reaches an agreement. The team will then apply the changes to the table and close the issue.

Please make each issue correspond to a single suggestion, but it is okay if the suggestion pertains to multiple cells in the table.

## Addition of New Sensing Methods

As mentioned above, it is inevitable that we will miss out particular sensing methods. In that case, we welcome anyone to submit a **Pull Request** for adding a new sensing method.

For the pull request, please use the `eval_template.csv` file we provided in this repository. The file contains all the columns we used in the table. For each score you assigned, please provide a brief reasoning. Once we accept the pull request, the reasoning will be imported into the table as well.

Feel free to submit multiple sensing methods within one single file.
