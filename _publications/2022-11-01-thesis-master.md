---
title: "Object attention and contextualization for vision and language navigation"
collection: publications
permalink: /publication/2022-11-01-thesis-master
date: 2022-11-14
paperurl: 'https://buscador.bibliotecas.uc.cl/permalink/56PUC_INST/bf8vpj/alma997397024403396'
citation: 'Earle. (2022). Object attention and contextualization for vision and language navigation.'
---
Vision-Language Navigation is a task where an agent must navigate different environments following natural language instructions. This demanding task is usually approached via machine learning methods, training the agent to learn navigation strategies that follow
what is said in the instruction and grounding it with what’s seen from its environment. However, there is still a gap between human performance and current Vision-Language Navigation models. These instructions usually refer to objects present in the agent’s scene, so proper understanding of what’s around the agent is necessary to understand where to go and when to stop. This understanding is left to be learned implicitly from the global features of its vision, which are not designed to do object detection. In this work, we propose methods to include and attend to objects during navigation in recurrent and transformer based architectures. We achieve a 1.6% improvement over the base models in unseen environments. But we also see that these models also take advantage of the objects to overfit on seen environments, increasing the gap between the validation seen and unseen splits.

[Download paper here](https://buscador.bibliotecas.uc.cl/permalink/56PUC_INST/bf8vpj/alma997397024403396)

Recommended citation:

```bib
 @thesis{earle_soto_2022,
  title={Object attention and contextualization for vision and language navigation},
  author={Earle, Benjamín and Soto, Alvaro},
  year={2022}
}
```
