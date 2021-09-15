# SANet
# Exploring Separable Attention for Multi-Contrast MR Image Super-Resolution

## Dependencies
* numpy==1.18.5
* scikit_image==0.16.2
* torchvision==0.8.1
* torch==1.7.0
* runstats==1.8.0
* pytorch_lightning==1.0.6
* h5py==2.10.0
* PyYAML==5.4

**Train**
```bash
cd experimental/SANet/
sbatch job.sh
```

Change other arguments that you can train your own model.

Citation

If you find SANet useful for your research, please consider citing the following papers:

```
@inproceedings{feng2021MINet,
  title={Multi-Contrast MRI Super-Resolution via a Multi-Stage Integration Network},
  author={Feng, Chun-Mei and Fu, Huazhu and Yuan, Shuhao and Xu, Yong},
  booktitle={International Conference on Medical Image Computing and Computer Assisted Intervention (MICCAI)},
  year={2021}
}
@article{feng2021exploring,
  title={Exploring Separable Attention for Multi-Contrast MR Image Super-Resolution},
  author={Feng, Chun-Mei and Yan, Yunlu and Liu, Chengliang and Fu, Huazhu and Xu, Yong and Shao, Ling},
  journal={arXiv preprint arXiv:2109.01664},
  year={2021}
}
```
