This is the replication package of the paper entitled _A Large-Scale Empirical Study on Code-Comment Inconsistencies_ presented at the [27th IEEE/ACM International Conference on Program Comprehension 2019 (ICPC 2019)](https://conf.researchr.org/home/icpc-2019) by the authors _Fengcai Wen, Csaba Nagy, Gabriele Bavota and Michele Lanza_.

The [rq1](rq1/) folder contains:
  * [systems.csv](rq1/systems.csv): This csv file contains the list of 1,500 GitHub projects mined in RQ1.
  * [statistical-analysis-method-comments.csv](rq1/statistical-analysis-method-comments.csv): This csv file reports the results of the statistical analysis (Fisher test and OR) when comparing the chances of  different categories of code changes to trigger methods' comments updates. The 1st column reports the two compared categories, the 2nd the p-value, the 3rd the OR, the 4th the lower bound of the 95% confidence interval for the OR, and the 5th the upper bound of the 95% confidence interval for the OR.
  * [statistical-analysis-class-comments.csv](rq1/statistical-analysis-class-comments.csv): This csv file reports the results of the statistical analysis (Fisher test and OR) when comparing the chances of  different categories of code changes to trigger class's comments updates. The 1st column reports the two compared categories, the 2nd the p-value, the 3rd the OR, the 4th the lower bound of the 95% confidence interval for the OR, and the 5th the upper bound of the 95% confidence interval for the OR.
  * [ast-level-changes.txt](rq1/ast-level-changes.txt): Instructions on how to get our database containing the 1.3 Billion AST-level changes extracted with GumTreeDiff.


The [rq2](rq2/) folder contains:
   * [keywords-matching-analysis.txt](rq2/keywords-matching-analysis.txt): explaining how we defined the lexical pattern used to identify commits likely fixing code-comment inconsistencies (i.e., those used in RQ2).
   * [tagged-commits.csv](rq2/tagged-commits.csv): The list of 500 tagged commits.
