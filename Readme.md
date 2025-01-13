### Mask autoencoder for TROPOMI $NO_2$ reconstruction

### Following steps
1. download POMINO-TROPOMI, A TROPOMI based NO2 product for Asia from https://www.pku-atmos-acm.org/acmProduct/#TROPOMI 
2. run `read_nc.ipynb` to extract $NO_2$ data from nc files
3. run `build_data.ipynb` to extract train, valid, test and mask data
4. run `torch_MAE_1d_final_20.ipynb` to train and evaluate the model