# Re:Invent 2021 - Deep learning applications with PyTorch 

### Distributed Training options on Amazon SageMaker with PyTorch + HuggingFace


* Training with a Single Node cluster using Multiple GPUs
* Distributed training with Multi-Node cluster using Multiple GPUs
* Distributed training with Multi-Node cluster using Multiple GPUs + **Data parallelism**
* Distributed training with Multi-Node cluster using Multiple GPUs + **Model Parallelism**


When training a model on a large amount of data, machine learning practitioners often turn to distributed training to reduce the time to train. In some cases, where time is of the essence, the business requirement is to finish training as quickly as possible or at least within a constrained time period. Then, distributed training is scaled to use a cluster of multiple nodes — not just multiple GPUs in a computing instance, but multiple instances with multiple GPUs.<br> <br>
If you want to scale your training even further, you can use more instances. However, you should choose a larger instance type before you add more instances. If you have made the jump from a single GPU on a p3.2xlarge to four GPUs on a p3.8xlarge, but decide that you require more processing power, you should always choose a p3.16xlarge before trying to increase instance count. When you keep your training on a single instance, performance is better than when you use multiple instances. Also, your costs are lower.
