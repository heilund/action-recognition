# Action-Recognition
Master thesis - using deep learning for action recognition

## Tools
Using the pre-trained model from st-gcn: https://github.com/yysijie/st-gcn (Kinetics), which is added as a submodule.

```
git clone https://github.com/heilund/action-recognition.git
```
```
git submodule init
```
```
cd st-gcn/
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
The downloaded models will be stored under ./models.

**NOTE:** Most/all commands that involves st-gcn requires the user to be in the 'st-gcn' folder

## TODO
1. Refactor code
2. Predict on multiple videos at once
3. Document (in a local README-file) in both **/st-gcn** and **/openpose** important files (scripts, generated files, etc.)
4. Understand both gendata, and prediction (the relationship between the different folders and files)
5. Research the possibility of (frame) padding videos < 300 frames
6. Research the possibility of stop frame translation > 300 frames

#
Stian Heilund & Sindre Eik de Lange
