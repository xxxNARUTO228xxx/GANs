## References

[dataset (image2anime)](https://github.com/TachibanaYoshino/AnimeGAN/tree/master/dataset)

[dataset (horse2zebra)](https://www.kaggle.com/balraj98/horse2zebra-dataset)

[cycleGAN paper](https://arxiv.org/pdf/1703.10593.pdf)

[LSGAN paper](https://arxiv.org/pdf/1611.04076.pdf)

## Some Results

I just checked on horse2zebra dataset for some epochs to ensure if it's working. I'm pretty sure it's not converged yet, you can notice it on cycle example:

![cycle_gen](https://user-images.githubusercontent.com/44481414/130331134-6725a049-5e83-454a-a9cd-3256f8f432fd.png)

However I found some good example too:

![cycleGAN_horse](https://user-images.githubusercontent.com/44481414/130331149-c92c47a7-3d16-421e-8b72-9832d3564c49.png)

I also tried some style transfer (I don't care how pathetic looks this grid made in paint):

![cycleGAN_anime2photo](https://user-images.githubusercontent.com/44481414/130331167-ba047433-3cb1-45e2-8464-c316ad5f6699.png)

![cycle](https://user-images.githubusercontent.com/44481414/130452567-3e876187-d462-45b3-aa94-0af08809de66.png)

Looks like it does nothing in photo2anime. As I noticed it blures image (as it must be because we don't care about small details in anime) and adds a sun. I'm sure better architectures for this mapping exist.
