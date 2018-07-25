# 1 Information Theory

**Motivation**: Information theory formalizes the concept of the “amount of randomness” or “amount of information”. These concepts can be extended to relative quantities among random variables. This section leads to Mutual Information (MI), a concept core to InfoGAN. MI extends entropy to the amount of additional information you yield from observing a joint sample of two random variables as compared to the baseline of observing each variable separately.

**Topics**:

1. Entropy
2. Differential Entropy
3. Conditional Entropy
4. Jensen’s Inequality
5. KL divergence
5. Mutual Information

**Required Reading**:

- [x] 1. Chapter 1.6 from Pattern Recognition and Machine Learning / Bishop. (“PRML”)
- [x] 2. A good intuitive explanation of Entropy, from Quora.

**Optional Reading**:

- [x] 1. [Notes on Kullback-Leibler Divergence and Likelihood Theory](https://arxiv.org/pdf/1404.2000.pdf)
- [ ] 2. For more perspectives and deeper dependencies, see Metacademy:
- [x] &nbsp;&nbsp;&nbsp;&nbsp;1. [Entropy](https://metacademy.org/graphs/concepts/entropy)
- [x] &nbsp;&nbsp;&nbsp;&nbsp;2. [Mutual Information](https://metacademy.org/graphs/concepts/mutual_information)
- [ ] &nbsp;&nbsp;&nbsp;&nbsp;3. [KL diverence](https://metacademy.org/graphs/concepts/kl_divergence)
- [ ] 3. [Visual Information Theory](https://colah.github.io/posts/2015-09-Visual-Information/)

**Questions**:

- [ ] 1. From PRML: 1.28, 1.31, 1.36, 1.37, 1.38, 1.39, 1.41.
- [ ] 2. How is Mutual Information similar to correlation? How are they different? Are they directly related under some conditions?
- [ ] 3. In classification problems, [minimizing cross-entropy loss is the same as minimizing the KL divergence of the predicted class distribution from the true class distribution](https://ai.stackexchange.com/questions/3065/why-has-cross-entropy-become-the-classification-standard-loss-function-and-not-k/4185). Why do we minimize the KL, rather than other measures, such as L2 distance?
