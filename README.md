# Machine Learning with PyTorch

Discover PyTorch for machine learning applications. Learn key concepts, build neural networks, and deploy models effectively. Ideal for beginners and experienced practitioners seeking practical skills in deep learning with PyTorch.

This training material is available under a [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/) license.

Please contact, [Erudio](http://erudio.one) for hands-on, instructor-led, onsite or remote, training. Our email is hi@erudio.one.


# Installing training materials

Before attending this course, please configure the environments you will need.  Within the repository, find the file `requirements.txt` to install software using `pip`, or the file `environment.yml` to install software using `conda`.  I.e.:

```bash
$ conda env create -f environment.yml
$ conda activate erudio.pytorch
(erudio.pytorch) $ jupyter notebook PyTorch-00_Outline.ipynb
```

Or

```bash
$ pip install -r requirements.txt
$ juypter notebook PyTorch-00_Outline.ipynb
```

## Generate the Conda environment

To share the environment, it is used:  

```shell
conda env export --from-history | grep -v "^prefix: " > environment.yml
```

So only packages that are explicitly requested will be included, and without the
prefix, which is the local folder where the package is installed.

After cloning this repository, you can restore the environment using:

```shell
conda env create -f environment.yml
```
