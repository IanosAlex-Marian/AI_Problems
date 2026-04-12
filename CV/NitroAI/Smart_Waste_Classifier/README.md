# Smart Waste Classifier

This project is part of the [NitroAI](https://judge.nitro-ai.org/competitions?page=1) challenges.

- [Jupyter Notebook](./main.ipynb)
- [Back to Main README](../../../README.md)

**Final Score: 100%**

## Documentation

This project utilizes a ResNet-50 architecture, pre-trained on the ImageNet-1K dataset, to classify waste images into six distinct categories. The images were preprocessed with resizing and data augmentations such as color jittering and flips to improve generalization. The model was fine-tuned over five epochs using the AdamW optimizer, yielding high classification performance.
