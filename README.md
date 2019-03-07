# CVFX-HW1-17

1. Training Process 

![](./TrainingProcess/0001.png)

![](./TrainingProcess/0002.png)

![](./TrainingProcess/0003.png)

2. Training cycleGAN

> Dataset — apple2orange (The right is the original image, the other one is the generated image)

![Alt text](./apple2orange/official_A/0001.png "apple2orange")

![Alt text](./apple2orange/official_A/0003.png "apple2orange")

![Alt text](./apple2orange/official_A/0006.png "apple2orange")

![Alt text](./apple2orange/official_B/0001.png "orange2apple")

![Alt text](./apple2orange/official_B/0003.png "orange2apple")

![Alt text](./apple2orange/official_B/0006.png "orange2apple")

> Dataset — iphone2dslr_flower (The right is the original image, the other one is the generated image)

![Alt text](./iphone2dslr_flower/official_A/0012.png "iphone2dslr")

![Alt text](./iphone2dslr_flower/official_A/0013.png "iphone2dslr")

![Alt text](./iphone2dslr_flower/official_A/0014.png "iphone2dslr")

![Alt text](./iphone2dslr_flower/official_B/0012.png "dslr2iphone")

![Alt text](./iphone2dslr_flower/official_B/0013.png "dslr2iphone")

![Alt text](./iphone2dslr_flower/official_B/0014.png "dslr2iphone")

3. Inference cycleGAN in personal image

> Dataset — apple2orange (The right is the original image, the other one is the generated image)

![Alt text](./apple2orange/A/0001.png "apple2orange")

![Alt text](./apple2orange/A/0003.png "apple2orange")

![Alt text](./apple2orange/A/0006.png "apple2orange")

![Alt text](./apple2orange/B/0001.png "orange2apple")

![Alt text](./apple2orange/B/0003.png "orange2apple")

![Alt text](./apple2orange/B/0006.png "orange2apple")

> Dataset — iphone2dslr_flower (The right is the original image, the other one is the generated image)

![Alt text](./iphone2dslr_flower/A/0004.png "iphone2dslr")

![Alt text](./iphone2dslr_flower/A/0002.png "iphone2dslr")

![Alt text](./iphone2dslr_flower/A/0003.png "iphone2dslr")

![Alt text](./iphone2dslr_flower/B/0001.png "dslr2iphone")

![Alt text](./iphone2dslr_flower/B/0002.png "dslr2iphone")

![Alt text](./iphone2dslr_flower/B/0003.png "dslr2iphone")



4. Compare with other method
   1. Color Transfer — Super Fast Color Transfer Between Images (https://github.com/jrosebr1/color_transfer)

   > Dataset — apple2orange

   ![Alt text](./SuperFastColorTransfer/apple2orange1.png "apple2orange")

   ![Alt text](./SuperFastColorTransfer/apple2orange2.png "apple2orange")

   ![Alt text](./SuperFastColorTransfer/apple2orange3.png "apple2orange")

   ![Alt text](./SuperFastColorTransfer/orange2apple1.png "orange2apple")

   ![Alt text](./SuperFastColorTransfer/orange2apple2.png "orange2apple")

   ![Alt text](./SuperFastColorTransfer/orange2apple3.png "orange2apple")

   > Dataset — iphone2dslr_flower

   ![Alt text](./SuperFastColorTransfer/iphone2dslr1.png "iphone2dslr")

   ![Alt text](./SuperFastColorTransfer/iphone2dslr2.png "iphone2dslr")

   ![Alt text](./SuperFastColorTransfer/iphone2dslr3.png "iphone2dslr")

   ![Alt text](./SuperFastColorTransfer/dslr2iphone1.png "dslr2iphone")

   ![Alt text](./SuperFastColorTransfer/dslr2iphone2.png "dslr2iphone")

   ![Alt text](./SuperFastColorTransfer/dslr2iphone3.png "dslr2iphone")

   > Analysis

   According to the above results, we think that the effect isn't as good as our expected. Because this algorithm focuses on the performance part, just calculate the mean and standard deviation of the image channels to do the color transfer. However, cycleGAN algorithm consumes more performance and lots of time in the training process, but the generated image is better than the output by this algorithm. 