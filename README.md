# robotics_recognition
Robotics Multimodal Deep Learning for Object Recognition


Applying CNN in to RGB-D dataset for fast and accurate object recognition 
Num of classes = 15
Used Libraries Tenforflow and Tensorlayer

Input Image size = (32,32)  self.image_shape = (32,32)
No. of layers = 3
Inputs {X : RGB, X_depth: Depth Image

All layers are designed with tensorlayer and backend with tensorflow

        base = tf.constant_initializer(value=0.1)
        Weight = tf.truncated_normal_initializer(stddev=0.04)


Reference:

1.	http://tensorlayer.readthedocs.io/en/stable/modules/layers.html
2.	https://arxiv.org/pdf/1507.06821.pdf
3.	https://www.tensorflow.org/tutorials/estimators/cnn
4.	https://www.tensorflow.org/api_docs/python/tf/layers/dropout

