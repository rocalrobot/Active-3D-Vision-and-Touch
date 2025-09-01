# RoCAL forked Active 3D vision and touch

#### Worked on by: Yicheng Zhu

This workspace is for Yicheng to keep track of the progress of replicating the forked repo. Yicheng is more familiar with markdown formatting than latex, that's why the note is written here. 
After the work has been implemented, this documentation will be trimmed down, cleaned up and added to the formal documentation. 

## Preparing the environment and file.
Conda is used to make a separate environment. 
Followed the instructions of the original repo.
```
conda create -n pytorch3d python=3.8
conda activate pytorch3d
conda install -c pytorch pytorch=1.7.1 torchvision cudatoolkit=10.2
conda install -c fvcore -c iopath -c conda-forge fvcore iopath
conda install -c bottler nvidiacub
conda install pytorch3d -c pytorch3d
```


`conda install -c pytorch pytorch=1.7.1 torchvision cudatoolkit=10.2`
This line spit error, then follow the [installation instruction](https://github.com/facebookresearch/pytorch3d/blob/main/INSTALL.md) here, ran this
`conda install pytorch=1.13.0 torchvision pytorch-cuda=11.6 -c pytorch -c nvidia`

And also this 
`conda install -c iopath iopath`
`conda install pytorch3d -c pytorch3d`

Install the jupyter notebook 
`conda install jupyter notebook`
`pip install "jupyterlab>=4" jupyter-lsp jupyterlab-lsp python-lsp-server[all]`


So far the installation of pytorch3d is okay, I will comeback and add more if the environment is not happy.

Download this repo to the computer.
`git clone https://github.com/rocalrobot/Active-3D-Vision-and-Touch.git`

Install dependencies
`$ pip install -r requirements.txt`
and install 
`$ python setup.py develop`

## Prepare dataset
`$ bash download_data.sh`


## Sanity Check
Start the jupyter notebook in a terminal 
`jupyter notebook`

Check if the working directory is in the root of the project `pwd` if not `%cd [to the correct place]`

Run the contents in the /notebook/simulation.ipynb, should have no problem


