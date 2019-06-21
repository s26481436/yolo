     #train.ipynb
     this is the different point between orignal git,
     optimizer: adam -> adagrad
     
     #evaluation.ipynb
     this file will evaluation ckpt accuracy.
     all of the evaluation settings are in core/config.py.
     # after evaluation, you should use mAP/main.py to caculation mAP.
     
     #warning
     if you want to demo the prediction via any weight, 
     you have to use freeze_graph.py to get .pb file.
     then you can use image_demo.py to demo the prediction.
     
     #image list txt file format:
     # image_path x_min, y_min, x_max, y_max, class_id  x_min, y_min ,..., class_id 
     
     #tips
     may you should set input size as smaller size,
     and set evaluation size as large size.
     then you maybe get a batter mAP.

#================================================================
#   Copyright (C) 2019 * Ltd. All rights reserved.
#
#   Editor      : VIM
#   Author      : YunYang1994
#   Created date: 2019-01-20 16:06:06
#   Description :
#
#================================================================
