# SF2942-calculator-programs-for-TI-84

This repository contains TI-84 calculator programs for the course **SF2942 HT24 Portfolio Theory and Risk Management** at **KTH Royal Institute of Technology**. The programs are highly aligned (no longer after Henrik took over the course at HT2024) to the exam questions and could save a lot of time for you in your exam. All programs are my original work. 

Use the programs on your own risk, the author takes no resonsibility.

## How to use
1. Download **TI Connect™ CE** from the [official website](https://education.ti.com/en/products/computer-software/ti-connect-ce-sw) and install it on your computer.
2. Follow the instructions to transfer the programs to your calculator.
3. On your calculator, press **PRGM** to display the **PRGM EXEC** menu. The programs in your calculator will appear in this menu. Select the program you want to use and press **ENTER**.
4. Enter the value of variables of your question. See specific instructions for the programs below. 
5. Get the answer.

## Program 
### INVSTNRF
Compute the optimal solution $(w_0, w)$ to some investment problems in the book [1]. The equations and propositions below refers to this book.
#### Input variables
| Variable in the calculator | Description |
| -- | ----------- |
| N | The number of risky assets |
| V | $V_0$ the initial capital |
| C | $c$ the tradeoff paramter |
| µ | The expected retrun of the risky assets as a list.  |
| Σ | The covariance matrix of the  risky assets as a matrix.  |
| R | $R_0$ The risk free return rate.  |
| σ0 | $\sigma_0$ The maximum variance in the constraint.  |
| µ0 | $\mu_0$ The minimum expectation in the constraint.  |

#### Output
$w_0$, $\mathbf{w}$.

#### Alternatives
##### 1. Without riskfree(Prop4.1)
Quadratic Investments Without a Risk-Free Asset (Problem: Equation 4.3, Solution: Proposition 4.1)

##### 2. With riskfree(Prop4.2)
Quadratic Investments with a Risk-Free Asset (Problem: Equation 4.7, Solution: Proposition 4.2)

##### 3. Min var(eq4.6)
Minimum variance portfolio (Problem: Example 4.4, Solution: Equation 4.6)

##### 4. Max E,≤σ(eq4.11)
Maximization of expectation with variance constraint (Problem: Equation 4.9, Solution: Equation 4.11)

##### 5. Min var,≥µ(eq4.12)
Minimization of Variance with expectation constraint (Problem: Equation 4.10, Solution: Equation 4.12)




## References
[1] F. Lindskog, H. Hult, O. Hammarlid, and C.-J. Rehn, Risk and portfolio analysis : principles and methods. Springer-Verlag New York, 2012.
