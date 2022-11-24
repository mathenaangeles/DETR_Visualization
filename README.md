# DETR Visualization for Object Detection with Occlusions
The [**DE**tection **TR**ansformer (DETR)](https://arxiv.org/abs/2005.12872) was released by Facebook AI in 2020.
![DETR](https://github.com/facebookresearch/detr/raw/master/.github/DETR.png)
Unlike traditional computer vision techniques, DETR approaches object detection as a direct set prediction problem. It consists of a set-based global loss, which forces unique predictions via bipartite matching, and a Transformer encoder-decoder architecture. Given a fixed small set of learned object queries, DETR reasons about the relations of the objects and the global image context to directly output the final set of predictions in parallel. Due to this parallel nature, DETR is very fast and efficient.
### Object Detection and Occlusions
Object detection is a computer vision technique for locating instances of objects in images or videos. Object detection algorithms typically leverage machine learning or deep learning to produce meaningful results. Occlusion occurs when an object that is being tracked is hidden (occluded) by another object or the surrounding environment.
### Transformers
The transformer architecture was introduced in the paper titled [Attention Is All You Need](https://arxiv.org/abs/1706.03762).

![Transformers](https://miro.medium.com/max/1400/1*Ir-j0HTT-IoWcZSyaE2F-A.png)
