To run training: 
--- python selfsupervised_denoising.py --dataset-dir=$HOME/datasets --validation-set=kodak --train=gauss25-blindspot-sigma_known --train-h5=imagenet_val.h5

Check help if you want to train other configurations: 
--- python selfsupervised_denoising.py --help

To run testing: 
--- python selfsupervised_denoising.py --dataset-dir=$HOME/datasets --validation-set=kodak --eval=$HOME/datasets/pretrained/network-00013-gauss25-blindspot-sigma_known.pickle
