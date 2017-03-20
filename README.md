# Conditional Image Generation

Term project repo for Deep Learning course at Universite de Montreal, see the [course webpage](https://ift6266h17.wordpress.com/project-description/) for full description.

# Dataset

The dataset is a a downsampled 64x64 version of [MSCOCO](http://mscoco.org/dataset/#overview), available [here](http://lisaweb.iro.umontreal.ca/transfert/lisa/datasets/mscoco_inpaiting/)

To get the data ready, simply run setup:
```shell
chmod +x setup # make sure `setup` is executable
bash setup
```

The `setup` script will create the `data` directory and download and extract images to `data/inpainting`. You should have the following structure in `data/`:

```shell
├── examples.py
├── inpainting
│   ├── dict_key_imgID_value_caps_train_and_valid.pkl
│   ├── train2014
│   ├── val2014
│   └── worddict.pkl
├── inpainting.tar.bz2
└── TO_READ.txt
```

