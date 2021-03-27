You require two different conda-environments since PyTorch and TensorFlow have incompatible dependencies.


# PyTorch
`conda create -n dlpt python=3.7`

`conda activate dlpt`

`conda install pytorch torchvision torchaudio nb_conda cudatoolkit=10.2 -c pytorch`

`pip install numpy matplotlib tqdm jupyter requests`


# TensorFlow
`conda create -n dltf python=3.7 tensorflow-gpu`

`conda activate dltf`

`conda install nb_conda`

`pip install numpy matplotlib tqdm jupyter`


# Run Notebooks
Start a jupyter notebook server with:
`jupyter notebook`
