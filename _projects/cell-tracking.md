---
title: Cell Tracking Project
description: Tracking cells in 2D/3D microscopy images
image: images/EMD.png
---

Object tracking is a fundamental problem in computer vision. In natural scene images, there are a lot of effective schemes, from classic model-based algorithms to recent [deep learning solutions](https://github.com/kjw0612/awesome-deep-vision#object-tracking). Common benchmarks can be found [here](https://motchallenge.net/). 

However, tracking cells, mostly in microscopy images (confocal or fluorescent), poses a very different problem. Intuitively, every cell looks almost the same in lots of situations. Suppose you mask out all the cells in one frame except one, and you want to find the corresponding cell in the next frame, this can be extremely difficult, especially when cells are packed densely. 

When retrospecting how I track cells by eyes in a sequence of images, I have implicitly used two strategies: anticipating the future positions by interpreting the motion/position of each cell in previous few frames or find matches between two small groups of cells, within which cell-to-cell correspondence can be easily determined. (For comparison, when you are tracking two cars, one yellow and one red, in a movie, it is nothing more than searching for car-shaped objects with either yellow or red color.)

Actually, two mainstream frameworks in the literature share a common spirit with the aforementioned intuitions. Namely,

* Framework 1: Tracking cells by propagating the position of each cell from frame to frame
* Framework 2: Tracking cells by finding an optimal matching between all cells in two (or more) consecutive frames

To this end, I developed an new approach for cell tracking problems. First, I proposed a matching algorithm based on [Earth Mover's Distance (EMD)](http://homepages.inf.ed.ac.uk/rbf/CVonline/LOCAL_COPIES/RUBNER/emd.htm) to perform matching between cells in consecutive frames. Based on that, I design a new hybrid scheme combining active contours (an important method in Framework 1) and EMD matching which takes the complimentary advantages of the two frameworks and achieves state-of-the-art performance in real applications. 


{% include section.html %}

## Related Publications:

{% include citation.html id="doi:10.1128/JB.00184-19" style="rich" %}

{% include citation.html id="doi:10.1007/978-3-319-10470-6_15" style="rich" %}

{% include citation.html id="doi:10.1007/978-3-319-24574-4_34" style="rich" %}


