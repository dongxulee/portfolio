---
layout: home
---

![Branching](https://raw.githubusercontent.com/dongxulee/portfolio/gh-pages/images/background/bg1.jpg)

### I lived in Ann Arbor for two years and graduated with a master degree in Quantitative Finance.

### I am living in New York now pursing a PHD in Financial Engineering.

### I watch a lot movies and I used to run a weekly movie night.


### I have a more detailed [résumé](./dongxuli.pdf) if you're into that sort of thing.

### I write code sometimes and I am into mathematics and finance.


- I have some collections of pet projects:
    * Predict the probability of a household to participate in stock trading. [link](./_projects/)
    * Thoughts on stock market. [link](./_projects/)
    * Two approaches to price binary options. [link](./_projects/)
    * Risk Monitor Program Structure for Trading Strategy. [link](./_projects/)
    * Editing image in an old fashing way. [link](./_projects/) 

- Solved a mathematical problem I found interesting:
       
    * Question: $$ 0 < t_1 < t_2 < t_3 < ... < t_n $$, show that n by n matrix $$\Sigma$$ with components $$\Sigma_{i,j} = min(t_i,t_j)$$ is a positive definite matrix.
    * Proof:
        The definition of positive definite: for any vector $$ x \in R^n$$ we have $$x^T \Sigma x > 0 $$.
        To begin with, define the brownian motion $$B_{t}$$, then $$B_{t}$$ follows a normal distibution with mean 0 and variance of t. 
          
        From the memoryless property of brownian motion, we have $$Cov(B_{t_{i}},B_{t_{j}})=min(t_{i},t_{j})$$ , then we cound write the $$\Sigma$$ as $$Cov(B,B)$$, where B is a n by 1 vector:
           
        $$\begin{array}{cccccccc}
        B & = & \left[\begin{array}{c}
        B_{t_{1}}\\
        B_{t_{2}}\\
        \vdots\\
        B_{t_{n}}
        \end{array}\right] & = & \left[\begin{array}{ccccc}
        1\\
        1 & 1\\
        1 & 1 & 1\\
        \vdots & \vdots & \vdots & \ddots\\
        1 & 1 & 1 & \cdots & 1
        \end{array}\right] & \left[\begin{array}{c}
        B_{t_{1}}\\
        B_{t_{2}}-B_{t_{1}}\\
        B_{t_{3}}-B_{t_{2}}\\
        \vdots\\
        B_{t_{n}}-B_{t_{n-1}}
        \end{array}\right] & = & A\tilde{B}\end{array}$$
        
        Where:
                   
        $$\begin{array}{c}
        A\end{array}=\left[\begin{array}{ccccc}
        1\\
        1 & 1\\
        1 & 1 & 1\\
        \vdots & \vdots & \vdots & \ddots\\
        1 & 1 & 1 & \cdots & 1
        \end{array}\right],\tilde{B}=\left[\begin{array}{c}
        B_{t_{1}}\\
        B_{t_{2}}-B_{t_{1}}\\
        B_{t_{3}}-B_{t_{2}}\\
        \vdots\\
        B_{t_{n}}-B_{t_{n-1}}
        \end{array}\right]$$

        So we could rewrite $$Cov(B,B)$$ as:
           
        $$\Sigma=Cov(B,B)=Cov(A\tilde{B},A\tilde{B})=ACov(\tilde{B},\tilde{B})A^{T}$$
               
        From the independent property of Brownian motion, $$B_{t_{1}}, B_{t_{2}}-B_{t_{1}},B_{t_{3}}-B_{t_{2}}, ... , B_{t_{n}}-B_{t_{n-1}}$$ are multually independent, then:   
           
        $$\Sigma=ACov(\tilde{B},\tilde{B})A^{T}=A\cdot diag\{t_{1},t_{2}-t_{1},t_{3}-t_{2},...,t_{n}-t_{n-1}\}\cdot A^{T}$$
           
        Finally for any vector $$x\in R^{n}$$, we have:   
           
        $$x^{T}\Sigma x=x^{T}(A\cdot diag\{t_{1},t_{2}-t_{1},t_{3}-t_{2},...,t_{n}-t_{n-1}\}\cdot A^{T})x$$
           
        Which is:   
           
        $$x^{T}\Sigma x=(A^{T}x)^{T}\cdot diag\{t_{1},t_{2}-t_{1},t_{3}-t_{2},...,t_{n}-t_{n-1}\}\cdot(A^{T}x)$$
           
        We could calculate:
           
        $$A^{T}x=\left[\begin{array}{c}
        x_{1}+x_{2}+...+x_{n}\\
        x_{2}+...+x_{n}\\
        \vdots\\
        x_{n}
        \end{array}\right]$$
           
        To further simplify:
           
        $$x^{T}\Sigma x=\sum_{k=1}^{n}(t_{k+1}-t_{k})(\sum_{j=k}^{n}x_{k})^{2}$$
            
        Obviously for any vector $$x\in R^{n}$$, we have: $$x^{T}\Sigma x>0$$.
        Hence the matrix $$\Sigma$$ is positive definite. 