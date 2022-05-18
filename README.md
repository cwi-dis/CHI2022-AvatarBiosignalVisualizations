## CHI 2022 paper: Social VR Avatar Biosignal Visualizations

This page contains source code and additional files for our CHI 2022 paper:
> ["Understanding and Designing Avatar Biosignal Visualizations for Social Virtual Reality Entertainment"](preprint/chi22-347.pdf)

<p align="center">
  <img src="imgs/chi2022_avatarbiosignals_example_skeuomorphic.gif" />
</p>

<!-- ![Example Skeuomorphjic](imgs/chi2022_avatarbiosignals_example_skeuomorphic.gif) -->

## Source Code

<!-- * [Avatar Biosignal Visualizations (Heart Rate, Breathing Rate)](source) -->

[BiosignalVisualizationPackage.unitypackage](source/BiosignalVisualizationPackage.unitypackage) is a Unity package file that includes biosignal visualizations with an example simulated biosignal. Note: This file does not include the jazz bar background.

Please follow the below instructions to get started:

1. Open Unity3D with the 'Universal Render Pipeline' template.
2. Import the package to Unity.
3. Read BiosignalManager.cs script to understand how the sample file works.
4. Adjust the BiosignalManager.cs and ExampleBiosignal.csv file if you want to make use of these visualizations in other projects.


## Preprint + Videos

* Preprint (.pdf) for [CHI '22 SocialVR Avatar Biosignals paper.](preprint/chi22-347.pdf)

* 30s video preview (.mp4):

[![30s video preview](imgs/30s_preview_screenshot.png)](https://abdoelali.com/chi2022-avatarbiosignals_vid_preview.mp4 "CHI 2022 Social VR Avatar Biosignals")

* 8-minute presentation on [SIGCHI's YouTube channel.](https://www.youtube.com/watch?v=yDFNzYbfGew)

## Supplementary Material

* [Supplementary material:](supplementary_material)
    -  A_vis_overview.mp4: Teaser video showing an overview of each biosignal visualization situated in the virtual jazz bar. Shows a view of the companion avatar as well as of the audience.

    - B_vis_detailed.mp4: Video showing each biosignal visualization (heart rate and breathing rate) across the three different signal rates tested: low, rest, and high.

    - C_post-hoc_interactions.pdf: A document showing the full set of pos-hoc interactions for perceived avatar arousal and for perceived distraction resulting from the contrast tests run with the ART-C tool. Refers to Sec. 4.4.1 and 4.4.2 in the paper.


## Citing this paper or code

**Please cite our paper in any published work that uses any of these resources.**

BiBTeX:
```
@inproceedings{Lee2022,
author = {Lee, Sueyoon and El Ali, Abdallah and Wijntjes, Maarten and Cesar, Pablo},
title = {Understanding and Designing Avatar Biosignal Visualizations for Social Virtual Reality Entertainment},
year = {2022},
isbn = {978-1-4503-9157-3/22/04},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3491102.3517451},
booktitle = {Proceedings of the 2022 CHI Conference on Human Factors in Computing Systems (submitted)},
location = {New Orleans, LA, USA},
series = {CHI '22}
}

  ```

ACM Ref Citation:

*Sueyoon Lee, Abdallah El Ali, Maarten Wijntjes and Pablo Cesar (2022). Understanding and Designing Avatar Biosignal Visualizations for Social Virtual Reality Entertainment. In CHI Conference on Human Factors in Computing Systems (CHI ’22). April 29-May 5, 2022, New Orleans, LA, USA. ACM, New York, NY, USA, 16 pages. https://doi.org/10.1145/3491102.3517451*

## Contact

If you have any questions about the above, you can drop us an email:

* [Sueyoon Lee](mailto:Sueyoon.Lee@cwi.nl)
* [Abdallah El Ali](mailto:aea@cwi.nl)


## Licenses

Code in this repo is released under [Mozilla Public
License 2.0](https://www.mozilla.org/en-US/MPL/2.0/).
