# Planter
![Planter Logo](src/images/logo.png)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
![GitHub release](https://img.shields.io/badge/pre--release%20tag-v0.2.0-orange)

## Introducing Planter
Planter is a modular framework for realising in one-click in-network machine learning algorithms. All you need to provide to Planter are a configuration file (```Name_data.py```) and a dataset. Planter will take it from there and offload your machine learning classification task into a programmable data plane.


## Current Planter

This work is currently under the peer-review process. _The source code will be made available once the peer-reviewed version is published._

We are welcoming to collaborations. It is excited to collaborate If you think in-network machine learning is helpful to your research or use case. If there are any potential interests, please feel free to contact my supervisor ```zilberman.noa@eng.ox.ac.uk``` and me ```changgang.zheng@eng.ox.ac.uk```.

## License

The files are licensed under Apache License: [LICENSE](./LICENSE). The text of the license can also be found in the LICENSE file.

## Citation
If you use this code, please cite our [papers](https://dl.acm.org/doi/abs/10.1145/3472716.3472846):

```
@article{zheng2022automating,
  title={Automating In-Network Machine Learning},
  author={Zheng, Changgang and Zang, Mingyuan and Hong, Xinpeng and Bensoussane, Riyad and Vargaftik, Shay and Ben-Itzhak, Yaniv and Zilberman, Noa},
  journal={arXiv preprint arXiv:2205.08824},
  year={2022}
}

@incollection{zheng2021planter,
  title={Planter: seeding trees within switches},
  author={Zheng, Changgang and Zilberman, Noa},
  booktitle={Proceedings of the SIGCOMM'21 Poster and Demo Sessions},
  pages={12--14},
  year={2021}
}
```
We are also excited to introduce several Planter related and supported papers:
```
@article{zheng2022iisy,
  title={IIsy: Practical In-Network Classification},
  author={Zheng, Changgang and Xiong, Zhaoqi and Bui, Thanh T and Kaupmees, Siim and Bensoussane, Riyad and Bernabeu, Antoine and Vargaftik, Shay and Ben-Itzhak, Yaniv and Zilberman, Noa},
  journal={arXiv preprint arXiv:2205.08243},
  year={2022}
}

@incollection{hong2022linnet,
  title={Linnet: Limit Order Books Within Switches},
  author={Hong, Xinpeng and Zheng, Changgang and Zohren, Stefan and Zilberman, Noa},
  booktitle={Proceedings of the SIGCOMM'22 Poster and Demo Sessions},
  year={2022}
}

@incollection{zang2022linnet,
  title={P4Pir: In-Network Analysis for Smart IoT Gateways},
  author={Zang, Mingyuan and Zheng, Changgang and Stoyanov, Radostin and Dittmann, Lars and Zilberman, Noa},
  booktitle={Proceedings of the SIGCOMM'22 Poster and Demo Sessions},
  year={2022}
}
```

Planter builds upon [IIsy](https://github.com/cucl-srg/IIsy) and is inspired by [SwitchTree](https://github.com/ksingh25/SwitchTree), [Qin](https://github.com/vxxx03/IFIPNetworking20), and [Clustreams](https://dl.acm.org/doi/pdf/10.1145/3482898.3483356).
