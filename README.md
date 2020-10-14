# UNET-Using-Numpy

### Environment recreation ###
-Install miniconda3-
conda install git
git clone https://github.com/udacity/deep-learning-v2-pytorch.git
cd deep-learning-v2-pytorch
conda create -n deep-learning python=3.8
conda install numpy jupyter notebook
conda install pytorch torchvision -c pytorch 
pip install -r requirements.txt
##
Extra thing to get Keras working ... is to install latest NVIDIA drivers, then verify that
nvcc --version, nvidia-smi   --> works
*also install cuda tools if you cant see cuda version on nvidia-smi box

## Important!  The latest requiremts are included in this folder(UNET-Using-Numpy)



##### Convert and move .png to .pgm ########
mogrify -format pgm ~/data/salt/images/*.png
mv ~/data/salt/images/*.pgm ~/data/salt/images/results
