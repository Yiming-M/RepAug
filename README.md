# RepAug

**Reproducible vision data augmentation in PyTorch.**

Essentially, images are converted to `torch.Tensor` first to be transformed. You can specify the argument `seed`, which will be passed to `np.random.default_rng`, to make your transform reproducible.

Currently supported transforms:
- RandomColorJitter
- RandomCrop, RandomResizedCrop
- RandomHorizontalFlip, RandomVerticalFlip
- RandomGaussianBlur
- Salt, Pepper
- RandomRotation, Random90Rotation, Random180Rotation

See `illustration.ipynb` for illustrations.

To install the package, you can run `pip install RepAug`.
