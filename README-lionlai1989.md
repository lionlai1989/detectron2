# Notes for `detectron2`

It documents the steps to run [the `detectron2` repository](https://github.com/facebookresearch/detectron2).

**Note:** Do not clone the `detectron2` repository. I cannot successfully run the example code in it.

## Installation

- Create a virtual environment

```shell
python3 -m venv venv_detectron2 \
&& source venv_detectron2/bin/activate
# pip: 22.0.2
# setuptools: 59.6.0

# Do not update pip, setuptools
# python3 -m pip install --upgrade pip setuptools
```

- Install Jupyter Notebook

```shell
python3 -m pip install "jupyter" "ipykernel" "notebook" "jupyterlab"
```

- Install `detectron2`

```shell
python3 -m pip install torch torchvision \
&& python3 -m pip install 'git+https://github.com/facebookresearch/detectron2.git' \
&& python3 -m pip install opencv-python
```
