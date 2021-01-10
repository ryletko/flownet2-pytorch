This is a fork of [NVIDIA/flownet2-pytorch](https://github.com/NVIDIA/flownet2-pytorch) with a support of backward processing, which is used in [ryletko/artistic-videos-python-wrapper](https://github.com/ryletko/artistic-videos-python-wrapper).

Simply add a flag --backward to the arguments of main.py and optical flow will be computed in an opposite order.

Works great under Ubuntu 18.04 with

  conda install pytorch==1.0.1 torchvision==0.2.2 cudatoolkit=10.0 -c pytorch

Don't forget to run install.sh.