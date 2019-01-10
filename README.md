# Object-Detection-YOLO
Implementing object detection using YOLO Framework in Python

You Only Look Once (YOLO) is a new and faster approach to object detection. Traditional systems repurposes classifiers to perform detection. Basically to detect any object, the system take a classifier for that object and then classifies its presence at various locations in the image. Other systems generate a potential bounding boxes in an image using region proposal methods and then run a classifier on these potential boxes. This results in a slightly efficient method. After classification, post — processing is used to refine the bounding boxes, eliminate duplicate detection, etc. Due to these complexities the system becomes slow and hard to optimize because each components have to be trained separately.

 For more information/better understanding visit my blog.
 Link Part 1: https://medium.com/@pratheesh.27998/object-detection-part1-4dbe5147ad0a
 Link Part 2: https://medium.com/@pratheesh.27998/object-detection-part2-6a265827efe1
