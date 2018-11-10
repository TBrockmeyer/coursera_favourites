# A Crash Course in Data Science
https://www.coursera.org/learn/data-science-course/
## What is Software Engineering for Data Science:
- SW Engineering: formalizes and abstracts functionality of a set of procedures or tools
- developing a well defined interface to the analysis
## At what point do you need to systematize common tasks and procedures across projects?
Basic rule of thumb:
- do something once: write code that does it, document it briefly
- do it twice: write a function
- do it three times: write a package and document its usage

## How is y typical Data Science Project structured?
Seven core phases:
- Question definition. (Spend some time on this, do it thoroughly - it will guide all following steps!) Specify the question behind the project you're asking. What is it you are interested in learning from data?
Types of questions: descriptive, exploratory, inferential, causal, predictive, mechanistic ...
- Data collection. Get data that can be used to explore the question
- Data exploration. Explore the data: is it suitable for the question you're asking? Is it complete enough (not too much data missing), are all necessary variables available?
- Solution sketch. Roughly sketch a possible solution, get a sense of what it will look like
- Formal Modelling. Specifically write down what questions you're asking, what parameters you're trying to estimate. Build the statistical model (this is a whole domain for itself, not treated here). This formal set of definitions and model will be used to challenge your approach later and iterate over the solution.
- Interpretation.
Sanity check: do the result somehow correspond with what you expected in the solution sketch phase?
Totality of evidence: which conclusions could be drawn from the results?
Weighting the evidence: which parts of the evidence are more reliable, which are more important than others? Get a sense of the totality of evidence with respect to answering the question.
- Iteration. If there is high discrepancy between expected results dive deeper, challenge your data and models until they withstand your most important doubts.
