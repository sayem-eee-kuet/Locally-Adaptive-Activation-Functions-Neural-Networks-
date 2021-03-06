Abstract: We propose two approaches of locally adaptive activation functions namely, layer-wise and neuron-wise locally adaptive activation functions, which improve the performance of deep and physics-informed neural networks. The local adaptation of activation function is achieved by introducing a scalable parameter in each layer (layer-wise) and for every neuron (neuron-wise) separately, and then optimizing it using a variant of stochastic gradient descent algorithm. In order to further increase the training speed, an activation slope based slope recovery term is added in the loss function, which further accelerates convergence, thereby reducing the training cost. On the theoretical side, we prove that in the proposed method, the gradient descent algorithms are not attracted to sub-optimal critical points or local minima under practical conditions on the initialization and learning rate, and that the gradient dynamics of the proposed method is not achievable by base methods with any (adaptive) learning rates. We further show that the adaptive activation methods accelerate the convergence by implicitly multiplying conditioning matrices to the gradient of the base method without any explicit computation of the\  conditioning matrix and the matrix-vector product. The different adaptive activation functions are shown to induce different implicit conditioning matrices. Furthermore, the proposed methods with the sloperecovery are shown to accelerate the training process.


1. LAAF_FunApproxi.py gives the self explanatory LAAF python code for 1D function approximation. Recommended python version 3.7 for this code.

For more details about the test case please refer our paper "AD Jagtap, K Kawaguchi, GE Karniadakis, Locally adaptive activation functions with slope recovery term for deep and physics-informed neural networks, arXiv preprint arXiv:1909.12228, 2019."

2. Deep_Learnig_Benchmark.zip is the set of python code, which implements locally adaptive activation functions. Please read "README_DeepLearningBenchmarks.txt" for more details.
   



