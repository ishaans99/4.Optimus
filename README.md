# Optimus

In this project for my optimization class, I implemented gradient descent, momentum, adagrad, adam, and accelerated gradient with hyperparameter tuning. I optimized the Booth, Beale, Rosenbrock, and Ackley functions, in each case finding a solution within a Euclidean distance of < 10^{-10} to the analytic solution. Note that answer.py was provided to me and was left unedited, the notebook served as a template where I wrote the optimization algorithms, and the I wrote the report entirely by myself.

As a fun fact, during the course of this project I noticed that the staff solution was inefficient for one of the algorithms we had been asked to implement; in particular the algorithm took longer to converge than what I had written, and in fact in the case of the provided example and hyperparameters, it actually diverged to NaN. The course staff were generous enough to give me a shoutout (and I think extra credit) for finding that bug and suggesting a fix.
