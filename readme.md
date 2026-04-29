# FUSE: First-Order and Second-Order Unified Synthesis in Stochastic Optimization (IEEE CAI 2025)

## Abstract 
Stochastic optimization methods have actively been playing a critical role in modern machine learning algorithms to deliver decent performance. While numerous works have proposed and developed diverse approaches, first-order and secondorder methods are in entirely different situations. The former is significantly pivotal and dominating in emerging deep learning but only leads convergence to a stationary point. However, second-order methods are less popular due to their computational intensity in large-dimensional problems. This paper presents a novel method that leverages both the first-order and second-order methods in a unified algorithmic framework, termed FUSE, from which a practical version (PV) is derived accordingly. FUSE-PV stands as a simple yet efficient optimization method involving a switch-over between first and second orders. Additionally, we develop different criteria that determine when to switch. FUSE-PV has provably shown a smaller computational complexity than SGD and Adam. To validate our proposed scheme, we present an ablation study on several simple test functions and show a comparison with baselines for benchmark datasets.

## commandline

``` 
pip install -r requirements.txt
```

``` 
python main.py --batch_size 512 --num_epochs 100 --dataset cifar --model dense_net --train_ratio 1.0 --num_layer 5
```
