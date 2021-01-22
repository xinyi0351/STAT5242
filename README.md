# Neural Style Transfer Improvement Method

### Intro

In this project, we implemented the neural style transfer based on existing study by [Gatys, etc](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Gatys_Image_Style_Transfer_CVPR_2016_paper.pdf). Briefly, Neural style transfer will take 3 images, a content image, a style image and an input image you want to style, then the style of style image will be transferred to the input image with content from content image. Our goal is to improve the transfer quality by adjusting intermediate layers used in content and style representations and discuss why certain layers are selected instead of others. An experimental model will be developed to compare with the baseline model that was designed by previous scholars. The performance of the models will be tested with respect of training iterations, random seeds and relative weight of content and style loss in the loss function.

### Input

Content images are:

```markdown
Content 1             |  Content 2
:-------------------------:|:-------------------------:
![img](/Users/xinyi0351/Documents/GitHub/STAT5242/images/content1.jpg) | ![img](/Users/xinyi0351/Documents/GitHub/STAT5242/images/content2.jpg)
```
