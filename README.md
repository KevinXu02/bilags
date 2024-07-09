# Bilags: An unofficial 3DGS Version of Bilateral Guided Radiance Field Processing
This repository contains the nerfstudio splatfacto implementation for SIGGRAPH (TOG) 2024 paper: "Bilateral Guided Radiance Field Processing" by Yuehao Wang, Chaoyi Wang, Bingchen Gong, and Tianfan Xue.

Only 2D training stage are implemented in this repo. An about 20% speed reduction is observed in the training stage. 

## Registering with Nerfstudio
Ensure that nerfstudio has been installed according to the [instructions](https://docs.nerf.studio/en/latest/quickstart/installation.html). Clone or fork this repository and run the commands:

```
conda activate nerfstudio
cd bilags/
pip install -e .
ns-install-cli
```

## Running the new method
The training should be exactly the same as splatfacto. For instance:
```
ns-train bilags --data [PATH]
```

## Acknowledgements
Thanks the authors of [Bilateral Guided Radiance Field Processing](https://github.com/yuehaowang/bilarf) for their amazing work.