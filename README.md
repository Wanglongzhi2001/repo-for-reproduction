# repo-for-reproduction
运行 custom_infer 文件夹里的 infer.py 进行推理，代码是 paddle-inference-demo 里的[示例](https://github.com/PaddlePaddle/Paddle-Inference-Demo/tree/master/python/gpu/resnet50)

量化后的模型提供在这个[链接](https://workdrive.zohopublic.com.cn/external/c00cacf9880dafd2ff3f8a5e0f331c2e35d070461549d6eec88df302cb3d219e/download)里，是运行 repo 里的 ptq_alexnet.py 文件夹而来，想要复现的话得自行配置好数据集，不想的话就直接用我提供的，代码参考自 PaddleSlim 的[示例](https://github.com/PaddlePaddle/PaddleSlim/tree/develop/example/quantization/ptq/classification)
