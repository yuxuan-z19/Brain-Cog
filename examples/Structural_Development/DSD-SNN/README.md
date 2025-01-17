# Enhancing Efficient Continual Learning with Dynamic Structure Development of Spiking Neural Networks #

## Requirments ##
* numpy
* timm
* pytorch >= 1.7.0
* collections
* argparse

## Introduction ##
Dynamic Structure Development of Spiking Neural Networks (DSD-SNN) for efficient and adaptive continual learning:   

grow new neurons and prune redundant neurons, increasing memory capacity and reducing computational overhead.  

verlap shared structure to leverage acquired knowledge to new tasks, empowering a single network to support multiple incremental tasks.   

We validate the effectiveness of the DSD-SNN multiple TIL and CIL benchmarks.

## Run ##
 

```CUDA_VISIBLE_DEVICES=0 python main_simplified.py```   

## Citation ##
If you find the code and dataset useful in your research, please consider citing:
```
@article{han2022developmental,
  title={Enhancing Efficient Continual Learning with Dynamic Structure Development of Spiking Neural Networks},
  author={Han, Bing and Zhao, Feifei and Zeng, Yi and Wenxuan, Pan and Shen, Guobin},
  booktitle = {Proceedings of the Thirty-First International Joint Conference on
               Artificial Intelligence, {IJCAI-23}},
  publisher = {International Joint Conferences on Artificial Intelligence Organization},
  year={2023}
  }

@article{zeng2023braincog,
  title={Braincog: A spiking neural network based, brain-inspired cognitive intelligence engine for brain-inspired ai and brain simulation},
  author={Zeng, Yi and Zhao, Dongcheng and Zhao, Feifei and Shen, Guobin and Dong, Yiting and Lu, Enmeng and Zhang, Qian and Sun, Yinqian and Liang, Qian and Zhao, Yuxuan and others},
  journal={Patterns},
  volume={4},
  number={8},
  year={2023},
  publisher={Elsevier},
}
```

Enjoy!
