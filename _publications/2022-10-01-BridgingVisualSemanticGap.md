---
title: "Bridging the Visual Semantic Gap in VLN via Semantically Richer Instructions"
collection: publications
permalink: /publication/2022-10-01-BridgingVisualSemanticGap
date: 2022-10-01
venue: 'ECCV'
paperurl: 'https://link.springer.com/chapter/10.1007/978-3-031-19836-6_4'
---
The Visual-and-Language Navigation (VLN) task requires understanding a textual instruction to navigate a natural indoor environment using only visual information. While this is a trivial task for most humans, it is still an open problem for AI models. In this work, we hypothesize that poor use of the visual information available is at the core of the low performance of current models. To support this hypothesis, we provide experimental evidence showing that state-of-the-art models are not severely affected when they receive just limited or even no visual data, indicating a strong overfitting to the textual instructions. To encourage a more suitable use of the visual information, we propose a new data augmentation method that fosters the inclusion of more explicit visual information in the generation of textual navigational instructions. Our main intuition is that current VLN datasets include textual instructions that are intended to inform an expert navigator, such as a human, but not a beginner visual navigational agent, such as a randomly initialized DL model. Specifically, to bridge the visual semantic gap of current VLN datasets, we take advantage of metadata available for the Matterport3D dataset that, among others, includes information about object labels that are present in the scenes. Training a state-of-the-art model with the new set of instructions increase its performance by 8% in terms of success rate on unseen environments, demonstrating the advantages of the proposed data augmentation method.

[Download paper here](https://link.springer.com/chapter/10.1007/978-3-031-19836-6_4)

Recommended citation:

```bib
@InProceedings{10.1007/978-3-031-19836-6_4,
  author="Ossand{\'o}n, Joaqu{\'i}n
    and Earle, Benjam{\'i}n
    and Soto, {\'A}lvaro",
  editor="Avidan, Shai
    and Brostow, Gabriel
    and Ciss{\'e}, Moustapha
    and Farinella, Giovanni Maria
    and Hassner, Tal",
  title="Bridging the Visual Semantic Gap in VLN via Semantically Richer Instructions",
  booktitle="Computer Vision -- ECCV 2022",
  year="2022",
  publisher="Springer Nature Switzerland",
  address="Cham",
  pages="54--69",
  isbn="978-3-031-19836-6"
}
```