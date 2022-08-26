```
conda create -n geo_env python=3.9.12
conda activate geo_env
conda config --env --add channels conda-forge
conda config --env --set channel_priority strict
conda install ipykernel matplotlib gdal richdem
conda install pytorch torchvision torchaudio cudatoolkit=11.6 -c pytorch -c conda-forge
conda install -c conda-forge segmentation-models-pytorch opencv gputil
conda install --no-update-deps -c conda-forge albumentations
```
