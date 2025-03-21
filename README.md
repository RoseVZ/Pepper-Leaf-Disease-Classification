


# Pepper Leaf Disease Classification  

A deep learning model using **CNNs (Convolutional Neural Networks)** to classify **pepper leaf diseases** based on image inputs. The model follows a sequential architecture and is implemented in a single Jupyter Notebook (`.ipynb` file).  

---

##  Model Architecture:  

```
Model: "sequential_2"
_________________________________________________________________
 Layer (type)                Output Shape              Param #   
=================================================================
 sequential (Sequential)     (32, 256, 256, 3)         0         
                                                                 
 sequential_1 (Sequential)   (32, 256, 256, 3)         0         
                                                                 
 conv2d (Conv2D)             (32, 254, 254, 32)        896       
                                                                 
 max_pooling2d (MaxPooling2D) (32, 127, 127, 32)       0         
                                                                 
 conv2d_1 (Conv2D)           (32, 125, 125, 32)        9248      
                                                                 
 max_pooling2d_1 (MaxPooling2D) (32, 62, 62, 32)       0         
                                                                 
 conv2d_2 (Conv2D)           (32, 60, 60, 32)          9248      
                                                                 
 max_pooling2d_2 (MaxPooling2D) (32, 30, 30, 32)       0         
                                                                 
 flatten (Flatten)           (32, 28800)               0         
                                                                 
 dense (Dense)               (32, 64)                  1843264   
                                                                 
 dense_1 (Dense)             (32, 2)                   130       
                                                                 
=================================================================
Total params: 1,862,786
Trainable params: 1,862,786
Non-trainable params: 0
```



---

## Requirements  

- Python  
- TensorFlow / Keras  
- OpenCV  
- NumPy  
- Matplotlib  

---
