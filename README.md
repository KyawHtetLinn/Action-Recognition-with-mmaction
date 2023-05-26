# Action Recognition with mmaction2

<p>We are going to train an action recognition model using the video dataset and the model can predict what the people are doing in the video.</p>
<p>The model can recognize well total 101 actions.The top1 accuracy is 0.794 and top5 accuracy is 0.942 .</p>

https://github.com/KyawHtetLinn/action-recognition-with-mmaction/assets/70162137/e6ed1cbb-6632-43a7-8700-28550f60c428  

https://github.com/KyawHtetLinn/action-recognition-with-mmaction/assets/70162137/ac75c017-8249-44e5-87de-2d9e36d918f9

<p>The above videos show the inference with non training videos</p>

<p>The model is trained with <a href="https://github.com/open-mmlab/mmaction2">mmaction library</a> with the <a href="https://github.com/open-mmlab/mmaction2/blob/main/configs/recognition/tsn/README.md">tsn networks</a> . </p>

## About Model 

* The model is trained with [Temporal Segment Network](https://github.com/open-mmlab/mmaction2/blob/main/configs/recognition/tsn/README.md) that is video-based action recognition networks.You can read the [paper](https://link.springer.com/chapter/10.1007/978-3-319-46484-8_2) for more detail.
* The dataset is [UCF101](https://www.crcv.ucf.edu/data/UCF101.php) and *train_split_1* is used in this training process and the split contain 9537 vidoes.
* 15 epochs 
* Trained with colab gpu.
* The training notebook is [here](https://github.com/KyawHtetLinn/action-recognition-with-mmaction/blob/main/train/action_recognition_mmaction(train).ipynb) .
* The inference notebook is [here](https://github.com/KyawHtetLinn/action-recognition-with-mmaction/blob/main/inference/action_recognition_mmaction(inference).ipynb) .

## Metrics

![alt text](https://github.com/KyawHtetLinn/action-recognition-with-mmaction/blob/main/assets/acc.png)

## References

* [mmaction2](https://github.com/open-mmlab/mmaction2)
* [mmaction2 datasets](https://mmaction2.readthedocs.io/en/latest/supported_datasets.html)
