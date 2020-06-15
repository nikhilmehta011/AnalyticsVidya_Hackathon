# AnalyticsVidya_Hackathon

### Hackathon's Link -- https://datahack.analyticsvidhya.com/contest/janatahack-computer-vision-hackathon/ 
<br/>

**First Step:** Datset is provided in the form of .zip file with test.csv containing test images. On extracting we get train and test images in a single folder along with train.csv that contains train image titles. Using Data_Sorting.ipynb train and test images are sorted.

<br/>

**Second Step:** On checking train images you will notice some images are in wrong directories. For instance, 1011.jpg is clearly a police car so it should be in class_1 directory rather than class_0. Next step is to manually picking these images and placing them into correct directories. There are few of these.
