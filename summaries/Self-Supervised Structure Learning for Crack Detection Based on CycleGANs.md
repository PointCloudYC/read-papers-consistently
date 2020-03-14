#### [20-03-14] [paper03]
Self-Supervised Structure Learning for Crack Detection Based on Cycle-Consistent Generative Adversarial Networks [summaries](https://github.com/PointCloudYC/read-papers-consistently/blob/master/summaries/Self-Supervised Structure Learning for Crack Detection Based on CycleGANs)

*Zhang Kaige, Zhang Yingtao, and Cheng H. D.*

`Jan, 2020 [GANs, CycleGANs, crack detection, self-supervised learning]`

****

### General comments on paper quality

- interesting paper, the proposed architecture is clearly described.

### Paper overview

- proposal; apply CycleGAN idea to generate the crack structure data for training crack detection task.

- core components; 1) data set includes a source(X) and target domain(Y), X is the crack patch and Y is the structure library; 2) Simultaneously train a CycleGAN on the two domain, so that any patch images can be translated into a GT-like structure image. 3) use the obtained data to do crack detection task. **Check fig1 for the framework and fig7 for the translated results**.

### Comments
