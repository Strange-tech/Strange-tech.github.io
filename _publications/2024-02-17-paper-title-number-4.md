---
title: 'LightUrban: Similarity Based Fine-grained Instancing for Lightweighting Complex Urban Point Clouds'
collection: publications
category: manuscripts
permalink: /publication/2024-08-19-paper-title-number-1
excerpt: ''
date: 2024-08-19
venue: 'Computer Graphics Forum'
paperurl: 'http://strange-tech.github.io/files/egPublStyle_PG2024_CRC_fixed.pdf'
# citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

Large-scale urban point clouds play a vital role in various applications, while rendering and transmitting such data remains challenging due to its large volume, complicated structures, and significant redundancy. In this paper, we present LightUrban, the first point cloud instancing framework for efficient rendering and transmission of fine-grained complex urban scenes. We first introduce a segmentation method to organize the point clouds into individual buildings and vegetation instances from coarse to fine. Next, we propose an unsupervised similarity detection approach to accurately group instances with similar shapes. Furthermore, a fast pose and size estimation component is applied to calculate the transformations between the representative instance and the corresponding similar instances in each group. By replacing individual instances with their group’s representative instances, the data volume and redundancy can be dramatically reduced. Experimental results on large-scale urban scenes demonstrate the effectiveness of our algorithm. To sum up, our method not only structures the urban point clouds but also significantly reduces data volume and redundancy, filling the gap in lightweighting urban landscapes through instancing.
