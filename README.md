# Chefies Machine-Learning

YOLOv8 and TFLite model that supports object detection of 5 Classes (Banana, Egg, Garlic, Shallot, Tomato). This is being made as a requirement to complete the Bangkit capstone project.
## Contributors ✨

Thanks goes to these wonderful people 👀 :

<table>
  <tbody>
    <tr>
      <td align="center"><a href="https://github.com/Shizu-ka"><img src="https://avatars.githubusercontent.com/u/58659139?v=4?s=100" width="100px;" alt="yosia"/><br /><sub><b>yosia</b></sub></a><br /><a href="https://github.com/Chefies/Machine-Learning" title="Code">💻</a></td>
      <td align="center"><a href="https://github.com/sfbernado"><img src="https://avatars.githubusercontent.com/u/93238724?v=4?s=100" width="100px;" alt="ten"/><br /><sub><b>ten</b></sub></a><br /><a href="https://github.com/Chefies/Machine-Learning" title="Code">💻</a></td>
      <td align="center"><a href="https://github.com/IkhlasulHanif"><img src="https://avatars.githubusercontent.com/u/88123202?v=4?s=100" width="100px;" alt="hanif"/><br /><sub><b>hanif</b></sub></a><br /><a href="https://github.com/Chefies/Machine-Learning" title="Code">💻</a></td>
    </tr>
    <tr>
  </tbody>
</table>

## Dataset
Our dataset is open source and available on Roboflow, link below : 

https://universe.roboflow.com/capstone-chefies/chefies

## Exporting Model
You can export the model to any format you want. Here is how :
1. Import
```python
!pip install ultralytics
import ultralytics
```
2. Export ([read more](https://docs.ultralytics.com/modes/export/#export-formats))
```python
!yolo export model=best.pt format=tflite
```
TFLite model is available on our releases.
