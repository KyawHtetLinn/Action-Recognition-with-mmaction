# action-recognition-with-mmaction

Training the action recognition model that can predict how the people are doing in the video.The model can recognize total 101 actions.
The top1 accuracy is 0.794 and top5 accuracy is 0.942 .

https://github.com/KyawHtetLinn/action-recognition-with-mmaction/assets/70162137/e6ed1cbb-6632-43a7-8700-28550f60c428  

https://github.com/KyawHtetLinn/action-recognition-with-mmaction/assets/70162137/ac75c017-8249-44e5-87de-2d9e36d918f9

The model is trained with [mmaction](https://github.com/open-mmlab/mmaction2) using the model [tsn](https://github.com/open-mmlab/mmaction2/blob/main/configs/recognition/tsn/README.md) . 

## About Model 

* The model is trained with [Temporal Segment Network](https://github.com/open-mmlab/mmaction2/blob/main/configs/recognition/tsn/README.md) that is video-based action recognition networks.You can read the [paper](https://link.springer.com/chapter/10.1007/978-3-319-46484-8_2) for more detail.
* The dataset is [UCF101](https://www.crcv.ucf.edu/data/UCF101.php) and the train split 1 is used in the training process and the split contain 9537 vidoes.
* 15 epochs
* Trained with colab gpu.
* The training notebook is [here](https://github.com/KyawHtetLinn/action-recognition-with-mmaction/blob/main/train/action_recognition_mmaction(train).ipynb) .
* The inference notebook is [here](https://github.com/KyawHtetLinn/action-recognition-with-mmaction/blob/main/inference/action_recognition_mmaction(inference).ipynb) .

## Metrics

![alt text](https://github.com/KyawHtetLinn/action-recognition-with-mmaction/blob/main/assets/acc.png)

## References

[mmaction2](https://github.com/open-mmlab/mmaction2)
