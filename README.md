# RoCAL forked Active 3D vision and touch

#### Worked on by: Yicheng Zhu

This workspace is for Yicheng to keep track of the progress of replicating the forked repo. Yicheng is more familiar with markdown formatting than latex, that's why the note is written here. 
After the work has been implemented, this documentation will be trimmed down, cleaned up and added to the formal documentation. 

## Preparing the environment and file.
Conda is used to make a separate environment. 
Following the instructions of the original repo.
```
conda create -n pytorch3d python=3.8
conda activate pytorch3d
conda install -c pytorch pytorch=1.7.1 torchvision cudatoolkit=10.2
conda install -c fvcore -c iopath -c conda-forge fvcore iopath
conda install -c bottler nvidiacub
conda install pytorch3d -c pytorch3d
```
