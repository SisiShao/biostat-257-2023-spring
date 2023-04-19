*Name: Sisi Shao*

### Overall Grade: 133/148

### Quality of report: 8/10

-   Is the homework submitted (git tag time) before deadline? 

Yes

-   Is the final report in a human readable format html? 

No (-2)

-   Is the report prepared as a dynamic document (Jupyter Notebook or Quarto Markdown) for reproducibility?

Yes

-   Is the report clear (whole sentences, typos, grammar)? Do readers have a clear idea what's going on and how are results produced by just reading the report? 

Yes

### Completeness, correctness and efficiency of solution: 65/75

- Q2 (15/15)


- Q3 (18/20)

Q3.3 Need to explicitly say that, with `Integer` input, the LLVM compiler is able to unroll the loop and simplify the expression into a two flop operation: `g(k) = 9765625k - 2441406`. But, with `Float64` input, the LLVM compiler only unrolls the loop but didn't simplify the expression. (-2)

- Q4 (11/15)

Q4.3 missing - need to explicitly mention catastrophic cancellation scenario 2 (-4)

- Q5 (20/20)

- Q6 (16/18)

Q6.5 - need to show the general result for any orthogonal matrix (-2)

- Q7 (8/10)

The result for only one benchmark is shown (-2)

	    
### Usage of Git: 8/10

- Are branches (`master` and `develop`) correctly set up? Is the hw submission put into the `master` branch?

- Are there enough commits? Are commit messages clear? 

Yes, commit messages could be more descriptive.
          
- Is the hw submission tagged? 

No (-2)

- Are the folders (`hw1`, `hw2`, ...) created correctly? 

Yes
  
- Do not put a lot auxiliary files into version control. 

### Reproducibility: 10/10

- Are the materials (files and instructions) submitted to the `master` branch sufficient for reproducing all the results? 

Yes

- If necessary, are there clear instructions, either in report or in a separate file, how to reproduce the results?

N/A

### Julia code style: 19/20

- Rule (1). Four space indenting rule. 

- Rule (2). 92 charcter rule.

- Rule (3). Space after comma rule.

Q6 - "randn(5,5)" --> "randn(5, 5)" (-1)

- Rule (4). No space before comma rule.

- Rule (5). Spae around binary operator rule.
