#ANSWER 1
Approximating complex posterior distributions in probabilistic models with smaller, tractable
distributions is the primary objective of variational inference (VI). In order to accomplish this,
VI converts the task of calculating a complex posterior distribution into one of optimization.
The goal is to minimize a divergence metric (such as the Kullback-Leibler divergence) between 
the approximate and true posterior distributions in order to select the distribution that is closest
to the true posterior from a family of approximating distributions.
 *Scalability
 *Convergence
 *Deterministic Nature
 *Computational Efficiency

 #Answer 2
 A simplified, tractable distribution called the variational distribution 𝑞(𝑤) q(w) is used in
 variational inference to approximate the genuine posterior distribution 𝑝(𝑤∣𝑥) p(w−x).
 It is utilized because it allows for effective and scalable inference by reducing the
 otherwise unmanageable problem of computing the posterior through optimization.

 #Answer 3
 The difference between two probability distributions is measured by KL divergence.
 It measures the degree to which the variational distribution 𝑞(𝑤) q(w) and the 
 genuine posterior 𝑝(𝑤∣𝑥) p(w−x) are similar in variational inference. 
 In order to find an accurate approximation of the posterior distribution
 for effective inference, the objective is to minimize this KL divergence.

 #Answer 4
 The Evidence Lower Bound (ELBO) in Variational Inference consists of two primary parts:
 How well the variational distribution describes the observed data is measured by the expected log-likelihood.
 The variational distribution's divergence from the previous distribution is penalized by negative KL divergence.
