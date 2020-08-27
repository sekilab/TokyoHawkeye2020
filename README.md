# Tokyo Hawkeye 2020 Pedestrian Dataset
## Download
[TH2020 dataset](https://sekilab-students.s3-ap-northeast-1.amazonaws.com/Gergely/TH2020/TH2020.zip)
## Contents
### Images
Images of dense urban areas of Tokyo, Japan taken from a high-altitude, steep (but not vertical) angle viewpoint. The listing of the areas are below:

![](/dataset.jpg)

### Head annotation
For every image the heads of pedestrians (including bikers) are annotated. The annotation format is a list of (x,y) coordinates in a .mat file.

### Segmentation annotation
The complete training set and nearly half of the validation set includes segmentation annotation, for seven classes:

* Building - 0
* Structure - 1
* Plant - 2
* Sidewalk - 3
* Vehicle - 4
* Road - 5
* Background - 6

The annotation format is single color channel .png file with seven possible color values. The respective color values are listed next to each class.

## Citation

If you find our dataset useful, please cite [our paper](https://www.mdpi.com/1424-8220/20/17/4855)

Csönde, G.; Sekimoto, Y.; Kashiyama, T. Crowd Counting with Semantic Scene Segmentation in Helicopter Footage. Sensors 2020, 20, 4855.

# License
Images on this dataset are available under the [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/) (CC BY-SA 4.0). The license and link to the legal document can be found next to every image on the service in the image information panel and contains the CC BY-SA 4.0 mark:
<br><a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/deed.en"><img alt="Creative Commons License" style="border-width:0" src="https://licensebuttons.net/l/by-sa/4.0/88x31.png" /></a><br />
