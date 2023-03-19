# TranSVAE

| Source (Original) | Target (Original) |  | Source (Original) | Target (Original) |
| :-: | :-: | :-: | :-: | :-: |
| ![src_original](figure/src_original.gif) | ![tar_original](figure/tar_original.gif) |  | ![src_original](figure/example2/src_original.gif) | ![tar_original](figure/example2/tar_original.gif) |
| |
| Reconstruction ($\mathbf{z}_d^{\mathcal{S}}$ + $\mathbf{z}_t^{\mathcal{S}}$) | Reconstruction ($\mathbf{z}_d^{\mathcal{T}}$ + $\mathbf{z}_t^{\mathcal{T}}$) |  | Reconstruction ($\mathbf{z}_d^{\mathcal{S}}$ + $\mathbf{z}_t^{\mathcal{S}}$) | Reconstruction ($\mathbf{z}_d^{\mathcal{T}}$ + $\mathbf{z}_t^{\mathcal{T}}$) |
| ![src_recon](figure/src_recon.gif) | ![tar_recon](figure/tar_recon.gif) |  | ![src_recon](figure/example2/src_recon.gif) | ![tar_recon](figure/example2/tar_recon.gif) |
| |
| Reconstruction ($\mathbf{z}_d^{\mathcal{S}} + \mathbf{0}$) | Reconstruction ($\mathbf{z}_d^{\mathcal{T}} + \mathbf{0}$) |  | Reconstruction ($\mathbf{z}_d^{\mathcal{S}} + \mathbf{0}$) | Reconstruction ($\mathbf{z}_d^{\mathcal{T}} + \mathbf{0}$) | 
| ![recon_srcZf](figure/recon_srcZf.gif) | ![recon_tarZf](figure/recon_tarZf.gif) |  | ![recon_srcZf](figure/example2/recon_srcZf.gif) | ![recon_tarZf](figure/example2/recon_tarZf.gif) |
| |
| Reconstruction ($\mathbf{0} + \mathbf{z}_t^{\mathcal{S}}$) | Reconstruction ($\mathbf{0} + \mathbf{z}_t^{\mathcal{T}}$) |  | Reconstruction ($\mathbf{0} + \mathbf{z}_t^{\mathcal{S}}$) | Reconstruction ($\mathbf{0} + \mathbf{z}_t^{\mathcal{T}}$) | 
| ![recon_srcZt](figure/recon_srcZt.gif) | ![recon_tarZt](figure/recon_tarZt.gif) |  | ![recon_srcZt](figure/example2/recon_srcZt.gif) | ![recon_tarZt](figure/example2/recon_tarZt.gif) |
| |
| Reconstruction ($\mathbf{z}_d^{\mathcal{S}} + \mathbf{z}_t^{\mathcal{T}}$) | Reconstruction ($\mathbf{z}_d^{\mathcal{T}} + \mathbf{z}_t^{\mathcal{S}}$) |  | Reconstruction ($\mathbf{z}_d^{\mathcal{S}} + \mathbf{z}_t^{\mathcal{T}}$) | Reconstruction ($\mathbf{z}_d^{\mathcal{T}} + \mathbf{z}_t^{\mathcal{S}}$) | 
| ![recon_srcZf_tarZt](figure/recon_srcZf_tarZt.gif) | ![recon_tarZf_srcZt](figure/recon_tarZf_srcZt.gif) |  | ![recon_srcZf_tarZt](figure/example2/recon_srcZf_tarZt.gif) | ![recon_tarZf_srcZt](figure/example2/recon_tarZf_srcZt.gif) |
