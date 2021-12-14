---
layout: article
title: Hierarchical clustering of driving scenarios
mode: immersive
header:
  theme: dark
article_header:
  type: overlay
  theme: dark
  background_color: '#203028'
  background_image:
    gradient: 'linear-gradient(135deg, rgba(34, 139, 87 , .4), rgba(139, 34, 139, .4))'
    src: /assets/images/cover.png
---
### Description

Test scenario generation for testing automated and autonomous driving systems requires knowledge about the recurring traffic cases, known as scenario types. The most common approach in industry is to have experts create lists of scenario types. This poses the risk both that certain types are overlooked; and that the mental model that underlies the manual process is inadequate. We extracted scenario types from real driving data by clustering recorded scenario instances, which are composed of time series.

We have constructed a living system of relevant scenario types that changes over time as we gather empirical evidences. The hierarchical format of the catalog helps user to have access to scenarios at three levels of granularity. Depending on context, one can decide which granularity to use. At the first level, scenarios are grouped based on the scene types and street type. At the second level, scenarios are grouped based on the trajectory of the ego vehicle, and at the third level scenarios are grouped based on the distances of the ego vehicle from its surrounding vehicles.

Scenarios are described in OpenScneario and can be used with Carla, esmini, and other simulators. Each scenario is accompanied by a gif file for visualization.

### Scenarios

- [2lanes](/scenarios//2lanes)
- [3lanes](/scenarios//3lanes)

<!-- ### License

MIT License -->

### Related publications

[Clustering traffic scenarios using mental models as little as possible](https://ieeexplore.ieee.org/document/9304636)


