Deep Learning Processing Speed
====
GPU VS CPU
------
Hardware is an important factor affecting the running speed of deep learning!
When running deep learning tasks, GPUs are typically much faster than CPUs. The main reason is the architectural difference between the two.

The GPU contains hundreds to thousands of small cores, which makes it very efficient at handling parallel tasks. Many operations in deep learning are well suited to parallelization. Therefore, GPUs are very suitable for running deep learning.

![](/images/DP1.png "GPU activity graph")

GPU activity graph, the batch size is 64

![](/images/128.png)

Batch size is 128

![](/images/256.png)

Batch size is 256


The larger the Batch size, the more data is processed in parallel.
As can be seen from the graph, GPU power increases when more data is processed in parallel. 
This is because GPU cores can execute identical instructions simultaneously, making them highly efficient for handling larger, parallel workloads.





Hao

![](/images/logo.png "fast.ai's logo")
