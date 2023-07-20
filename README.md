https://www.geeksforgeeks.org/human-activity-recognition-with-opencv/
https://github.com/pm1715/HAR_Project

Required Download:
https://www.dropbox.com/s/065l4vr8bptzohb/resnet-34_kinetics.onnx?dl=1


```
 python HAR.py --model resnet-34_kinetics.onnx --classes Actions.txt --input videos/example_activities.mp4 --gpu 1 --output output.mp4

(Replace HAR.py with your python file name and Actions.txt with your kinetics dataset text file name. )
```


```
For the webcam, we will use this

python HAR.py --model resnet-34_kinetics.onnx --classes Actions.txt


```