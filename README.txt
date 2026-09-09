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

DeepLabv3+ test metrics
-----------------------
         ET_dice: 0.7206
          ET_iou: 0.5633
         TC_dice: 0.8037
          TC_iou: 0.6719
         WT_dice: 0.8650
          WT_iou: 0.7621
       mean_dice: 0.7965
        mean_iou: 0.6658
  pixel_accuracy: 0.9937

Try to improve them. Is visible a marked overfitting after epoch3.
