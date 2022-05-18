# DLC installation on ubuntu > 18.04

How to install DLC on ubuntu 20.04 (tested in Pop OS 20.04)

Assuming Anaconda is already installed

Step 1. Open the terminal and create a conda environment

`conda create -n DLC python=3.8`

then

`conda activate DLC`

Step 2. Install wxpython with ubuntu wheels

`python3 -m pip install -U -f https://extras.wxpython.org/wxPython4/extras/linux/gtk3/ubuntu-20.04 wxPython`

Step 3. Install DeepLabCut with gui support

`pip install 'deeplabcut[gui]'`

then test the gui support with `python -m deeplabcut`

