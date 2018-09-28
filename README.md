# Action-Recognition
Master thesis - using deep learning for action recognition

## Tools
- **OpenPose**:
```
https://github.com/yysijie/openpose.git
```
- **st-gcn** (Kinetics): Added as a submodule.

```
git clone https://github.com/heilund/action-recognition.git
```
```
git submodule init
```
```
cd st-gcn/
```
```
git submodule update --init/
```
## *From st-gcn*
**Installation**
```
cd torchlight; python setup.py install; cd ..
```
**Get pretrained models**
```
bash tools/get_models.sh
```
The downloaded models will be stored under *st-gcn/models*.

**NOTE:** Most/all commands that involves st-gcn requires the user to be in the 'st-gcn' folder

## TODO
1. Refactor code
2. Predict on multiple videos at once
3. Understand both gendata, and prediction (the relationship between the different folders and files)
4. Research the possibility of (frame) padding videos < 300 frames
5. Research the possibility of stop frame translation > 300 frames
6. Add a "Quick Start" to README? 

#
Stian Heilund & Sindre Eik de Lange
