# OPTIMIZATION-MODEL

*COMPANY*:  CODTECH IT SOLUTIONS

*NAME*:  RAJAT SINGHAL

*INTERN ID*:  CT04DG3154

*DOMAIN*:  DATA SCIENCE

*DURATION*:  4 WEEKS

*MENTOR*:  NEELA SANTOSH

##Description of this project using Jupyter Notebook
In this Jupyter Notebook project, linear programming is employed to solve a classic resource allocation problem in furniture production. The objective is to determine the optimal number of tables and chairs to manufacture in order to maximize profit, subject to a set of resource and market constraints. Using the `PuLP` library in Python, the task is formulated as a maximization problem. The decision variables represent the number of tables and chairs to be produced, both of which are constrained to be non-negative integers. Each table yields a profit of \$200 and requires 30 board feet of wood, 5 hours of labor, and 3 hours of finishing. Similarly, each chair yields \$75 in profit and consumes 10 board feet of wood, 2 hours of labor, and 1 hour of finishing. The total available resources are limited to 600 board feet of wood, 120 hours of labor, and 80 hours of finishing.

To incorporate realistic production requirements, the model includes a minimum production constraint of 5 tables and a market demand constraint limiting the maximum number of chairs to 50. These constraints ensure that the solution adheres to practical business conditions. The optimization problem is solved using PuLP’s built-in solver, and the status of the solution is reported to confirm whether an optimal solution has been found. The final output includes the optimal number of tables and chairs to produce, along with the total profit resulting from this production plan.

Further analysis is carried out to evaluate resource utilization. For each resource (wood, labor, and finishing), the notebook calculates and displays how much was used relative to what was available, along with the corresponding percentage. This helps in understanding whether any resources were underutilized or fully consumed. Moreover, the notebook identifies the binding constraints in the solution. Binding constraints are those that are fully used up—meaning any small change to these constraints would directly impact the optimal solution. This is essential for managerial decision-making as it pinpoints bottlenecks in the production process.

Although shadow prices, or dual values, are mentioned in the context of sensitivity analysis, the notebook notes whether they are available for each constraint. Shadow prices indicate how much the objective function (profit) would change if there were one additional unit of a resource. This is useful for understanding the value of acquiring more resources or relaxing certain constraints.

To enhance the interpretability of results, the notebook includes a visualization section using Matplotlib and Seaborn. It prepares bar plots to visually compare the available versus used quantities for each resource, giving an intuitive understanding of which constraints are more critical. The visual output complements the numerical results and makes it easier to present findings to non-technical stakeholders.

Overall, this notebook provides a comprehensive walkthrough of formulating, solving, and analyzing a linear programming problem. By integrating Python libraries for optimization, data handling, and visualization, it showcases a practical approach to operations research and decision science. The step-by-step structure—from problem definition and constraints to solving and interpretation—demonstrates effective use of Jupyter Notebook for modeling and solving real-world optimization problems.

#OUTPUT

<img width="1156" height="758" alt="Image" src="https://github.com/user-attachments/assets/9c1d093f-8cef-42d8-a3e9-da7d38f512ca" />
