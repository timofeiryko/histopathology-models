## Pretrained models for classification of histopathological images

In this repo you can find code to classify histopathological images with deep learning models. These models are trained on the lung cancer data from the [Kaggle dataset](https://www.kaggle.com/datasets/andrewmvd/lung-and-colon-cancer-histopathological-images).

You can also use this code to train on your own data. It is built using tensorflow and keras. For example, you can integrate these models with [Deepslide](https://github.com/BMIRDS/deepslide/) or other pipelines.

If you like it, please, upwote [this notebook on Kaggle]() and star this repo!

## Usage

You can download the corresponding folders for each of the model from the [MEGA drive](https://mega.nz/folder/pixmTb6b#AS9bXaag9cu5wHHZZVRY-A).

To load model weights, move these folders to your project and use the following code:

```python
saved_model = model.load_weights('ModelName')
```

Model names are: `ResNet50`, `ResNet50-dropout`, `InceptionV3`, `SimpleCNN`.

In the repo itself you can find just the notebook

## Which models are better?

You can find detalied analysis of these models in the notebook. In general, fine-tuned models are better than `SimpleCNN`, probably the best choice is `ResNet50-dropout`. However, it is recommended to test different approaches for your particular dataset. You can fork my Kaggle notebook and train these models. Don't forget to upvote :)

## How to contribute?

If you have trained these models on your own data (for example, not only for lung cancer, it's possible), you are welcome to add new models to this repo and to the drive, just open an issue!

## Collaboration!

If you have any questions, suggestions for cooperation or offers - you are welcome to contact me:

tg: [@timofeiryko](https://t.me/timofeiryko)

FaceBook: [Timofei Ryko](https://www.facebook.com/timofeiryko/)

LinkedIn: [Timofei Ryko](https://www.linkedin.com/in/timofeiryko/)

Twitter: [timofeiryko](https://twitter.com/timofeiryko)

GitHub: [timofeiryko](https://github.com/timofeiryko)

