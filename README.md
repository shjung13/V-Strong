# V-STRONG: Visual Self-supervised Traversability Learning for Off-road Navigation
> Sanghun Jung, JoonHo Lee, Xiangyun Meng, Byron Boots, and Alexander Lambert <br>
> University of Washington <br>
> ICRA 2024 <br>

<a href="https://sites.google.com/view/visual-traversability-learning"><img src="https://img.shields.io/badge/webpage-visual.traversability.learning-blue?style=for-the-badge"></a>
<a href="https://arxiv.org/abs/2312.16016"><img src="https://img.shields.io/badge/arxiv-2312.16016-red?style=for-the-badge"></a>

>**Abstract**<br>
Reliable estimation of terrain traversability is critical for the successful deployment of autonomous systems in wild, outdoor environments. Given the lack of large-scale annotated datasets for off-road navigation, strictly-supervised learning approaches remain limited in their generalization ability. To this end, we introduce a novel, image-based self-supervised learning method for traversability prediction, leveraging a state-of-the-art vision foundation model for improved out-of-distribution performance. Our method employs contrastive representation learning using both human driving data and instance-based segmentation masks during training. We show that this simple, yet effective, technique drastically outperforms recent methods in predicting traversability for both on- and off-trail driving scenarios. We compare our method with recent baselines on both a common benchmark as well as our own datasets, covering a diverse range of outdoor environments and varied terrain types. We also demonstrate the compatibility of resulting costmap predictions with a model-predictive controller. Finally, we evaluate our approach on zero- and few-shot tasks, demonstrating unprecedented performance for generalization to new environments. 
<p align="center">
  <img src="assets/overview.png" />
</p>

## Repo Construction Progress
Status | Name | Date
:---:| --- | ---
⬜️| Code under preparation | 09/04/2025
⬜️| Code release | Nov. 2025 (expected)

## License
To be updated

## Acknowledgement
This research was developed with funding from the Defense Advanced Research Projects Agency (DARPA). The views, opinions and/or findings expressed are those of the author and should not be interpreted as representing the official views or policies of the Department of Defense or the U.S. Government.

## Cite
```
@inproceedings{jung2024v,
  title={V-strong: Visual self-supervised traversability learning for off-road navigation},
  author={Jung, Sanghun and Lee, JoonHo and Meng, Xiangyun and Boots, Byron and Lambert, Alexander},
  booktitle={2024 IEEE International Conference on Robotics and Automation (ICRA)},
  pages={1766--1773},
  year={2024},
  organization={IEEE}
}
```
