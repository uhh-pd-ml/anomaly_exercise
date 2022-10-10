# anomaly_exercise
Exercise on Anomaly Detection in Particle Physics for the 3rd Terascale School of Machine Learning.

Authors: [Gregor Kasieczka](https://github.com/gkasieczka), [Louis Moureaux](https://github.com/lmoureaux), [Tobias Quadfasel](https://github.com/loeschet) and [Manuel Sommerhalder](https://github.com/msommerh) (University of Hamburg).

## Contents

- general introduction about anomaly detection, patricularly in a Particle Physics context
- Anomaly Detection using weak supervision methods
- Anomaly Detection with Autoencoders

## Recommended software

There are two ways this exercise can be run:

1. Using google Colab: In this case, no prior installation of Software is required. However, you need a google account to use the Colab service. For accessing the notebook, please follow this [Link](https://colab.research.google.com/drive/1M8CEmhGDZaoouZYckhG_GoZZNy2vEr3J?usp=sharing). Once you arrive at the notebook, click `File -> Save a copy in drive` to get your personal copy of it, which you can then run and edit as you please.
2. Running locally: Of course, you can run this tutorial on your local computer or any other computing infrastructure you have access to. The notebook is located in this repository in the `exercise_anomaly_detection.ipynb` file. We provided an `environment.yml` file which you can use to install an `anaconda` environment that contains all necessary software packages. If you do not want to install `anaconda`, here is a list of recommended `python` packages that should be available on your machine in order to run the exercise:

- `pytorch` (including the respective version of `cudatoolkit` in case a GPU is available and should be used)
- `pandas`
- `pytables`
- `numpy`
- `matplotlib`
- `scikit-learn`
- `h5py`
- `vector`

**Note:** It is highly recommended to run this exercise using a **GPU** if available. To use a GPU in Colab, klick `Runtime->Change runtime type` and choose `GPU` from the drop-down list under `Hardware accelerator`.

## Solutions

We also provide solutions to this exercise. These can be found in another Colab notebook under this [Link](https://colab.research.google.com/drive/1yHxu-26hIOlGhOqKLO4O6aUvz4JDWyYq?usp=sharing), or as another `ipynb` notebook, which is located in the `solution` branch of this repository.