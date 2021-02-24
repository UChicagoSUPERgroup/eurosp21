# SoK: Context Sensing for Access Control in the Adversarial Home IoT - Supplement Evaluation Table

The repository contains [an online version of the evaluation table (Table 2-3)](https://docs.google.com/spreadsheets/d/1tcAb3B0-iyIoBK8ioKDfu4XtHkmp4Rwaf8RuKfn0OoY/edit?usp=sharing) in paper `SoK: Context Sensing for Access Control in the Adversarial Home IoT` (paper link).

## Goal

The goal of providing an online version of the evaluation we did for various sensing methods (Table 2-3 in the paper) is several folded.

1. The online version gives us a chance to offer a more detailed reasoning for each score we assigned. This is not possible to achieve within the page limit of the paper.
2. As we acknowledged in the paper, some of the scores are based on the teams' own judgement, which could be subjective. 
3. There could be sensing methods that are not aware by the team, but should be included and considered. With time going on, it is inevitable that there will be new sensing methods being proposed and developed, and the table included here needs update.

To overcome these problems, we decide to make this table as an ongoing effort of the community. Anyone who disagrees with certain scores, or would like to add a particular sensing method can share their thoughts here. We will detail the method in next part.

## Questions / Suggestions / Requests of Revision

Any one who has questions or suggestions about certain scores we give in the table, please submit your question or suggestion as an **Issue** to this repository.

Please use the following format when submitting an issue:

```
Paper / Product - Criteria:
[The paper / product - criteria pair you have question with (e.g. Google Voice Match - Replay Attack). If your question or suggestions corresponds to multiple scores, you can put multiple pair here.]

Cell ID (Optional):
[The cell id (e.g., H6) of the score you would like to change. If your question or suggestions corresponds to multiple scores, you can put multiple cell ID here. This is mainly for helping us locate the score.]

Questions / Suggestions / Requests of Revision:
[State your questions, suggestions, or requests of revision. ]

References:
[Please include any references that you used or you believe to be helpful.]
```

Once we saw the issue, we will be happy to open any discussions related until everyone reaches to an agreement. The team will then apply the changes to the Table and closed the issue.

Each issue should be corresponds to one single suggestion, although th

## Addition of New Sensing Methods

As mentioned above, it is inevitable that we will miss out particular sensing methods. In that case, we welcome anyone to submit a **Pull Request** for an addition of a new sensing method.

For the pull request, please use the `eval_template.csv` file we provided in this repository. The file contains all the columns we used in the table. For each score you assigned, please provide a brief reasoning. Once we accept the pull request, the reasoning will be imported into the table as well.

You can submit multiple sensing methods within one single file.
