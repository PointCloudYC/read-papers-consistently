# GANs
- what? propose **a new neural network to estimate generative models via an adversarial process**.
  - comprised of 2 networks: generator and discriminator network.
  - Example(counterfeiter to fake the currency, police) to understand the GANs; Thru competitions, both teams improve their methods until the counterfeits are indistinguishable from the genuine training data.  
  - Essentially, it is a minimax two-player game; one player is the generator ,another is the discriminator, both can be defined by a MLP.
  - Equilibrium: in the arbitrary space of G and D, a unique sol. exists, w. G recovering the training data distribution and D equal to 0.5 everywhere.


- how?
  - an coding example; check the DL w. Python book ch08 8.5. and hands-on ML ch17 GANs part.

- limitation;
  - The existence of adversarial examples does suggest GAN training could be inefficient, because they show that it is possible to make modern discriminative networks confidently recognize a class w.o. emulating any of human-perceptible attributes of that class.

- issues;
  - GANs are based on a minimax game; GANs is not an optimization problem but a minimax game; The game terminate at **a saddle point** that is a minimum w.r.t. one player's strategy and a maximum w.r.t. the other player's strategy.
  - Adversarial examples V.S. GANs; refer to those examples are similar but misclassified.
  
## other references
* [GAN — What is Generative Adversary Networks GAN? - Jonathan Hui - Medium](https://medium.com/@jonathan_hui/gan-whats-generative-adversarial-networks-and-its-application-f39ed278ef09)
>

* [GAN — Some cool applications of GANs. - Jonathan Hui - Medium](https://medium.com/@jonathan_hui/gan-some-cool-applications-of-gans-4c9ecca35900)
>