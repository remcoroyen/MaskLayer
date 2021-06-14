## MaskLayer: Enabling scalable deep learning solutions by training embedded feature sets

**The code (both the basic code + applications) will be released soon. Estimated time of arrival: max 1st of June 2021 (EDIT: Due to deadlines, ETA delayed to 1st of August)**

**Authors:** <a href="https://www.linkedin.com/in/remcoroyen/" target="_blank">Remco Royen</a>, <a href="http://www.etrovub.be/LeonDenis" target="_blank">Leon Denis</a>, <a href="http://www.etrovub.be/qbolsee" target="_blank">Quentin Bolsée</a>, <a href="http://www.etrovub.be/phu" target="_blank">Pengpeng Hu</a> and <a href="http://www.etrovub.be/AdrianMunteanu" target="_blank">Adrian Munteanu</a> - Vrije Universiteit Brussel (VUB). The first author has been funded by a FWO-SB scholarship.

![MaskLayer architecture](https://github.com/remcoroyen/MaskLayer/blob/main/paper_figs/masklayer_arch.png)

### Introduction

This repository is the code release of the work from our [journal paper](https://www.sciencedirect.com/science/article/pii/S089360802100023X?via%3Dihub), published in Neural Networks in May 2021 (the preprint can be accessed via [ResearchGate](https://www.researchgate.net/publication/348645114)). We propose a novel and generic neural network layer that is able to achieve quality scalable feature sets.

Deep learning-based methods have shown to achieve excellent results in a variety of domains, however, some important assets are absent. Quality scalability is one of them. In this work, we introduce a novel and generic neural network layer, named MaskLayer. It can be integrated in any feedforward network, allowing quality scalability by design by creating embedded feature sets. These are obtained by imposing a specific structure of the feature vector during training. To further improve the performance, a masked optimizer and a balancing gradient rescaling approach are proposed. Our experiments show that the cost of introducing scalability using MaskLayer remains limited. In order to prove its generality and applicability, we integrated the proposed techniques in existing, non-scalable networks for point cloud compression and semantic hashing with excellent results. To the best of our knowledge, this is the first work presenting a generic solution able to achieve quality scalable results within the deep learning framework.

### Citation
If you find our work useful in your research, please consider citing:

	@article{royen2021masklayer,
		title={MaskLayer: Enabling scalable deep learning solutions by training embedded feature sets},
		author={Royen, Remco and Denis, Leon and Bolsee, Quentin and Hu, Pengpeng and Munteanu, Adrian},
		journal={Neural Networks},
		volume={137},
		pages={43--53},
		year={2021},
		publisher={Elsevier}
	}
	
### License
Our code is released under MIT License (see LICENSE file for details).

## Contact
If you have any questions or suggestions regarding this repo or the paper, please feel free to contact me (remco.royen@vub.be).
