# Udacity Dataset

```
├── Udacity_Dataset/
│    ├── HMB_3/
│    ├── LICENSE.mit.md
│    ├── README.md
```

The *Udacity* dataset has been derived from the open-source Udacity dataset for self-driving cars (https://github.com/udacity/self-driving-car) and is redistributed here with modified resolution and in gray-scale to match the configuration of our ultra-low-power camera.
This release includes the same test set used in the original [DroNet](https://github.com/uzh-rpg/rpg_public_dronet).
It is composed of 5280 `.pgm` images with resolution 324x244, each tagged with a steering label.
The labels for all images are a subset of those available in the original Udacity dataset and are organized in the `file_name,steering_angle` format inside the `labels.csv` file.