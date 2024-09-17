# FEED: Facial Extreme Emotions Dataset
Official repository for the FEED: Facial Extreme Emotions Dataset.


## Dataset Download Links:
- [Google Drive](https://drive.google.com/drive/folders/1bxtEC76HH-CeGMFBT0xCm45UHSjrw3Rh?usp=sharing)
- [Yandex Disk](https://disk.yandex.com/d/4L3DyD3883HdCw)
  

## Video Naming Conventions:
- `*_C.mp4`: Video recorded from the central camera.
- `*_R.mp4`: Video recorded from the right camera.
- `*_L.mp4`: Video recorded from the left camera.

## Video Content Descriptions:
- `blinks_*`: The person performs blinks (typically both eyes together and each eye separately).
- `eyes_*`: The person performs eye movements.
- `rotations_*`: The person performs head rotations.
- `tongue_rot_*`: The person performs head rotations while being asked to demonstrate their tongue during the rotations.
- `MAU_mild/strong_*`: The person performs the Main Action Units (Surprise, Fear, Disgust, Anger, Happiness, Sadness) in mild and strong intensities without head rotations or tongue expressions.
- `FF_*`: The person performs the Main Action Units in strong intensity with head rotations and attempts to make the expressions as asymmetrical as possible.
- `FF_NR_*`: The person performs the Main Action Units in strong intensity without head rotations, focusing on making the expressions as asymmetrical as possible.
- `tongue_em_*`: Similar to `FF_NR_*`, but the person is asked to use their tongue in expressions where possible.
- `random_*`: The person is asked to perform random extreme expressions continuously for 2-3 minutes.

For more details, please visit the [project page](https://neeek2303.github.io/EMOPortraits/) and refer to the EMOPortraits: Emotion-enhanced Multimodal One-shot Head Avatars [paper](https://arxiv.org/abs/2404.19110).

## Important Notes:

1. **License**:  
   The dataset is made available under the Creative Commons BY-NC-SA 4.0 license. You are free to use, redistribute, and adapt it for non-commercial purposes, provided that you:
   - (a) Give appropriate credit by citing our paper.
   - (b) Indicate any changes that you’ve made.
   - (c) Distribute any derivative works under the same license.

2. **Dataset Sharing**:  
   If you have the capacity to store and share the dataset, please consider uploading it to cloud storage and sharing the link here by adding it to an Issue titled "Dataset Link Resharing." The dataset may become unavailable on Yandex Disk and especially Google Drive due to storage limitations on the author’s account.

3. **Dataset Composition** (as of September 1, 2024):  
   The dataset currently consists of 17 identities. Of the 23 identities mentioned in the paper:
   - 2 identities are pending final approval for publication.
   - 1 identity has technical issues with the video, which might be resolved in the future.
   - 3 identities have withdrawn their initial consent for publication.
