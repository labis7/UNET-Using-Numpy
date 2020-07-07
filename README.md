# UNET-Using-Numpy

### Environment recreation ###
http://conda.pydata.org/docs/install/quick.html#linux-miniconda-install
conda install git
git clone https://github.com/udacity/deep-learning-v2-pytorch.git
cd deep-learning-v2-pytorch
conda install numpy jupyter notebook
conda create -n deep-learning python=3.8
conda install pytorch torchvision -c pytorch 
pip install -r requirements.txt
##
Extra thing to get Keras working ... latest drivers so 
nvcc --version, nvidia-smi   --> works
and then cuda tools if you cant see cuda version on nvidia-smi box

## Important!  The latest requiremts are included in this folder(UNET-Using-Numpy)



##### Convert and move .png to .pgm ########
mogrify -format pgm ~/data/salt/images/*.png
mv ~/data/salt/images/*.pgm ~/data/salt/images/results
