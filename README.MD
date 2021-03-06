# Tracking the tracker: Time Series Analysis in Python From First Principles

All codes are using python 2.7.

The source code are original work of the author, so any resemblance to existing work on the Internet would be merely coincidental. This work is free from every form of plagarism, so the references of the research papers used in writing the codes are provided.

A number of kalman filtering solution has been biased towards location-based problems. This talk aims to change that stereotype by describing kalman filtering in a form suited for time series analysis and other kinds of applications.

Kalman filtering is a estimation technique that is suited for time series analysis (filtering, forecasting), sensor fusion, and localization. This can be used as a basis for converting static models into incremental learning models.

Kalman filtering works using a two-step process of prediction and correction under some conditions can ensure that we can have a self-correcting system as sample size increases.


Why would the author spend time implementing from first principle or reinventing the wheel. This was done to ensure that the audience internalize the concept described as the implementation are free of unneccessary optimizations that destroy the understanding of the concept.

# Run the Test
Download code and navigate to tests folder. The run

$ python -m tests -v

# API
See the examples folder.

# TO DO
* Set up project for patch contributions.

* Make the extended kalma filter's non linear equation easy to use.

* Replace first order differentiation to automatic differentiation tool like autograd.

* Reorganize in an installable python package with pip.

* Robust documentation.

* Ad more testcases.

# Q & A

is the code production ready?
You may want to offload aspects of the processing to Cython. Otherwise, it can be suitable for your needs. This is an experimental project.

is the code free from bugs?
This code does not have any intentional bug. However, like Donald Knuth would say 'Beware of bugs in the above code; I have only proved it correct, not tried it.'. Only one caveat here, I have demonstrated a use case to show the usefulness of the code.


Feel free to reach out to me for any discussion about anything.
Twitter:  @kenluck2001
Linkedin: https://www.linkedin.com/in/kenluck2001/


# References

1. Castanon, D., & Karl, C. W. SC505: Stochastic processes. Retrieved 06/15, 2017, from http://www.mit.edu/people/hmsallum/GradSchool/sc505notes.pdf

2. Wellstead, P. E. & Karl, C. W. (1991). Self-tuning Systems: Control and Signal Processing. Chichester, United Kingdom: John Wiley & Sons Ltd.

3. Hamilton, J. D. (1994). Time series analysis. Chichester, United Kingdom: Princeton University Press.

4. Julier, S. J. The scaled unscented transformation. Retrieved 06/15, 2017, from https://www.cs.unc.edu/~welch/kalman/media/pdf/ACC02-IEEE1357.PDF

5. Terejanu, G. A. Extended kalman filter tutorial. Retrieved 06/15, 2017, from https://www.cse.sc.edu/~terejanu/files/tutorialEKF.pdf

6. Wan , E. A., & Merwe, R. (2000). The unscented kalman filters for nonlinear estimation. IEEE Adaptive Systems for Signal Processing, Communications, and Control Symposium, pp. 153-158.

7. Welch, G., & Bishop, G. An introduction to the kalman filter. Retrieved 06/15, 2017, from https://www.cs.unc.edu/~welch/media/pdf/kalman_intro.pdf 
