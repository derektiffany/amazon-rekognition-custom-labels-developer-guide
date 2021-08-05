# Step 7: Locate objects with bounding boxes<a name="tutorial-draw-bounding-boxes"></a>

If you want your model to detect the location of objects within an image, you need to identify what the object is and where it is in the image\. A bounding box is a box that isolates an object in an image\. You use bounding boxes to train a model to detect different objects in the same image\. You identify the object by assigning a label to the bounding box\. 

**Note**  
If you're training a model to find objects, scenes, and concepts, you don't need to do this step\.

For example, if you want to train a model that detects Amazon Echo Dot devices, you draw a bounding box around each Echo Dot in an image and assign a label named *Echo Dot* to the bounding box\. The following image shows a bounding box around an Echo Dot device\. The image also contains an Amazon Echo without a bounding box\.

![\[Image NOT FOUND\]](http://docs.aws.amazon.com/rekognition/latest/customlabels-dg/images/dot.jpg)

 In this step, you use the console to draw bounding boxes around the objects in your images\. You also identify objects within the image by assigning labels to the bounding box\. 

Before you can add bounding boxes, you must add at least one label to the dataset\. For more information, see [Step 5: Add labels](tutorial-create-labels.md)\.

**To add a bounding box**

1. In the dataset gallery, choose the images that you want to add bounding boxes to\.

1. Choose **Draw bounding box**\. A series of tips are shown before the bounding box editor is displayed\.

1. In the **Labels** pane on the right, select the label that you want to assign to a bounding box\.

1. In the drawing tool, place your pointer at the top\-left area of the desired object\.

1. Press the left mouse button and draw a box around the object\. Try to draw the bounding box as close as possible to the object\. 

1. Release the mouse button\. The bounding box is highlighted\.

1. Choose **Next** if you have more images to label\. Otherwise, choose **Done** to finish labeling\.  
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/rekognition/latest/customlabels-dg/images/draw-bounding-box.png)

1. Repeat steps 1–7 until you have created a bounding box in each image that contains objects\. 

1. Choose **Save changes** to save your changes\. 

1. Choose **Exit** to exit labeling mode\.