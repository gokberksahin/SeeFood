# SeeFood

[SeeFood](Paper.pdf) is a Random Forest model that estimates the calories and volume of a basic food. The [baseline](https://github.com/Liang-yc/CalorieEstimation) work identifies the food on a image and then tries to categorize its shape and each shape has a corresponding mathematical formula to estimate the volume and calories. Instead of using these formulas we claimed that a machine learning model can do better job estimating the volume and calories. 

![](giphy.gif)

Course Web Page: [BBM 406 Fall 2018 Fundamentals of Machine Learning](https://web.cs.hacettepe.edu.tr/~aykut/classes/fall2018/bbm406/project.html)

### Our Blog Posts:

You can see what we did week by week with more details.

- https://medium.com/bbm406f18/week-1-seefood-be1097c7876a
- https://medium.com/bbm406f18/week-2-seefood-ae381ea34757
- https://medium.com/bbm406f18/week-3-seefood-a511dd2f17a7
- https://medium.com/bbm406f18/week-4-seefood-59f1b759b173
- https://medium.com/bbm406f18/week-5-seefood-f495a76ded70
- https://medium.com/bbm406f18/week-6-seefood-52720a73823d
- https://medium.com/bbm406f18/week-7-seefood-959bc06ec32

## DataSet

We used ECUST Food Dataset. You can see more information about our used dataset [ECUSTFD](https://github.com/Liang-yc/ECUSTFD-resized-). 

## Object Detection

We used Faster R-CNN model to detect foods. We compared a few different variations but we obtained the best results at [Facter R-CNN inception v2 coco](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/detection_model_zoo.md). 


## Prediction Results

| Method Name | Volume RMSE | Calorie RMSE |
| --- | --- | --- |
| KNN | 21.06 | 45.69 |
| Random Forest | 13.21 | 30.37 |



