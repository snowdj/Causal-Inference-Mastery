# Introduction 
This repository will consists of graduate level notes on causal inference. The notes are a consise summary of material covered in popular causal inference textbook and relevant research papers related. The outline and associated primary references are listed below.

# Contribution Possibilities
I am currently focusing on making detailed notes on the topics listed in the outline below. In the long run I would hope to have simulation code that illustrate the fundemental theorems and causal inference methods. For example it is well known that under randomized binary treatment the ATE is identified. This can be easily argued using a simulation that could be included under the "Introduction to Causal Inference" folder. Feel free to conduct pull requests for including relevant simulations into this repository (popular languages such as R, Stata, Python or Matlab are all fine for this).   

# Outline
Although the folders are not ordered, the outline below is my recommended ordering of going through these materials.

1. Introduction to Causal Inference
   * POM, ATE, ATT, ATU, QTE and corresponding identification assumptions
2. Selection on Observables
   * Experiments, CIA, subclassification, matching, and regression
3. Directed Acyclical Graphs (Causal Graphs)
   * Back door criterion, bad controls, collider bias, and do(.) operator
4. Parameter Identification 
   * Definitions and examples for both point and partial identification
5. Instrumental Variables
   * IV assumptions, LATE, and experiments without compliance
6. Regression Discontinuity
   * RD assumptions, Sharp, Fuzzy, and Kink RD
7. Panel Data
   * FE and RE discussion and interactive FE
8. Differences-in-differences
   * DD assumptions and DD model extensions
9. Inference of causal parameters
   * Fisher's exact test, t-test, and clustered standard errors
10. Empirical Resarch Papers
    * Notes on papers from good journals that apply the above methods.
11. Additional Material
    * Notes from causal inference papers and other relevant material

# Primary Text References
- Cunningham, S. (2018). Causal Inference The Mix Tape. 
- Hansen, B. (2018). Graduate Notes in Econometrics. University of Wisconsin.  
- Imbens, G., & Rubin, D. (2015). Causality: The Basic Framework. In Causal Inference for Statistics, Social, and Biomedical Sciences.  
- Morgan, S., & Winship, C. (2014). Counterfactuals and Causal Inference: Methods and Principles for Social Research.
- Angrist, J. D., Pischke, J. S. (2008). Mostly Harmless Econometrics: An Empiricist's Companion. Princeton University Press. 

# Primary Paper References
- Alberto, A. & Matias, C. (2018). Econometric Methods for Program Evaluation. Annual Review of Economics. 
- Athey, S. & Imbens, G. (2017). State of Econometrics and Policy Evaluation. Journal of Economics Perspectives. 

# Lecture Slides References
- [Scott Cunningham (2017). Causal Inference and Research Design.](http://scunning.com/teaching/lectures.pdf)
- [Teppei Yamamoto (2016). Introduction to Causal Inference.](http://web.mit.edu/teppei/www/teaching/Keio2016/)

# Video References
- Alberto, A., Joshua A., & Walters C. (2017). Cross-Section Econometrics. American Economic Association Webcast.
