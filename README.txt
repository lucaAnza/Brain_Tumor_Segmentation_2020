The actual situation is the following.
In the file Unet you can find the implementation of UNET alone.
In the file deeplabv3 can find the implementation of DEEPLAVBV3 alone.

The best results of Unet are the following:


UNET results
------------
         ET_dice: 0.7635
          ET_iou: 0.6175
         TC_dice: 0.7604
          TC_iou: 0.6134
         WT_dice: 0.8724
          WT_iou: 0.7737
       mean_dice: 0.7988
        mean_iou: 0.6682
  pixel_accuracy: 0.9939


The model weight are in the directory weights/.

In the final_version.ipynb is possible to find the to submit. Before the submission you should find a model that improve the Unet results that are use
as baseline. After that you insert into the final version the architecture and try to execute everything.

The actual result for deeplabv3 are:

DeepLabv3+ test metrics V1
-----------------------
         ET_dice: 0.7363
          ET_iou: 0.5827
         TC_dice: 0.8255
          TC_iou: 0.7028
         WT_dice: 0.8783
          WT_iou: 0.7830
       mean_dice: 0.8134
        mean_iou: 0.6895
  pixel_accuracy: 0.9942


DeepLabv3 V2
----------
         ET_dice: 0.7916
          ET_iou: 0.6550
         TC_dice: 0.8434
          TC_iou: 0.7292
         WT_dice: 0.8962
          WT_iou: 0.8118
       mean_dice: 0.8437
        mean_iou: 0.7320
  pixel_accuracy: 0.9950

Mean Dice improvement: 0.84369167979052.

TODO : Make a test in the new V2 version that fixes some warning + add weight path.
TODO : Training again V2 and save the weights. Then finally add everything in the final version and test both model.
TODO : Translate UNET Architecture img explaination from Itian to English
TODO : Add this into references.

### References

1. Ronneberger, O., Fischer, P., & Brox, T. (2015).  
   *U-Net: Convolutional Networks for Biomedical Image Segmentation*.  
   In Medical Image Computing and Computer-Assisted Intervention (MICCAI), pp. 234–241.

2. Chen, L.-C., Zhu, Y., Papandreou, G., Schroff, F., & Adam, H. (2018).  
   *Encoder-Decoder with Atrous Separable Convolution for Semantic Image Segmentation*.  
   European Conference on Computer Vision (ECCV), pp. 801–818.

3. Chollet, F. (2017).  
   *Xception: Deep Learning with Depthwise Separable Convolutions*.  
   IEEE Conference on Computer Vision and Pattern Recognition (CVPR), pp. 1251–1258.

4. Hu, J., Shen, L., & Sun, G. (2018).  
   *Squeeze-and-Excitation Networks*.  
   IEEE Conference on Computer Vision and Pattern Recognition (CVPR), pp. 7132–7141.

5. Wu, Y., & He, K. (2018).  
   *Group Normalization*.  
   European Conference on Computer Vision (ECCV), pp. 3–19.

6. Ramachandran, P., Zoph, B., & Le, Q. V. (2017).  
   *Searching for Activation Functions*.  
   arXiv preprint arXiv:1710.05941.

7. Chen, L.-C., Papandreou, G., Schroff, F., & Adam, H. (2017).  
   *Rethinking Atrous Convolution for Semantic Image Segmentation*.  
   arXiv preprint arXiv:1706.05587.





