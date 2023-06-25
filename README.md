
# Final Project Deep Learning
Person Classification with Gender using VGG16 Model
- Task by <b>Andi Hendra, S.Si., M.Kom.</b>


## Team 6 Member

- Anugrah Aidin Yotolembah (<b>F551 20 093</b>)
- Fajar Dzulnufrie Hafriadi (<b>F551 20 089</b>)
- Asmaun Hasyanah Sary (<b>F551 20 092</b>)
- Mutiara Sari Muti (<b>F551 20 091</b>)
- Iga Mawarni (<b>F551 20 099</b>)

## 🔗 Dataset
Link : [Google-Drive](https://drive.google.com/drive/folders/1nJxZKzr_mIxRbbQxulk503rwWRHIWUnU?usp=sharing)
```Gherkin
PersonDataset/
|-- train/
|   |-- Anugrah Aidin Yotolembah/
|       |-- Anugrah Aidin Yotolembah_001.jpg
|       |-- Anugrah Aidin Yotolembah_002.jpg
|       |-- ...
|   |-- Fajar Dzulnufrie Hafriadi/
|       |-- Fajar Dzulnufrie Hafriadi_001.jpg
|       |-- Fajar Dzulnufrie Hafriadi_002.jpg
|       |-- ...
|   |-- Asmaun Hasyanah Sary/
|       |-- Asmaun Hasyanah Sary_001.jpg
|       |-- Asmaun Hasyanah Sary_002.jpg
|       |-- ...
|   |-- Iga Mawarni/
|       |-- Iga Mawarni_001.jpg
|       |-- Iga Mawarni_002.jpg
|       |-- ...
|   |-- Mutiara Sari/
|       |-- Mutiara Sari_001.jpg
|       |-- Mutiara Sari_002.jpg
|       |-- ...
|-- test/
|   |-- Anugrah Aidin Yotolembah/
|       |-- Anugrah Aidin Yotolembah_001.jpg
|       |-- Anugrah Aidin Yotolembah_002.jpg
|       |-- ...
|   |-- Fajar Dzulnufrie Hafriadi/
|       |-- Fajar Dzulnufrie Hafriadi_001.jpg
|       |-- Fajar Dzulnufrie Hafriadi_002.jpg
|       |-- ...
|   |-- Asmaun Hasyanah Sary/
|       |-- Asmaun Hasyanah Sary_001.jpg
|       |-- Asmaun Hasyanah Sary_002.jpg
|       |-- ...
|   |-- Iga Mawarni/
|       |-- Iga Mawarni_001.jpg
|       |-- Iga Mawarni_002.jpg
|       |-- ...
|   |-- Mutiara Sari/
|       |-- Mutiara Sari_001.jpg
|       |-- Mutiara Sari_002.jpg
|       |-- ...
```



## Workflow

    1. Load Data
    2. Preprocessing Data
    3. Creating Model
    4. Training/Validation with Visualization
    5. Testing including visual and caption

    
## Environment

```python
NumPy (import numpy as np): untuk operasi numerik pada data array.
Pandas (import pandas as pd): untuk manipulasi dan analisis data.
OS (import os): untuk mengakses file system dan mengambil alamat direktori dari dataset.
TensorFlow (import tensorflow as tf): library utama untuk membuat dan melatih model deep learning.
Keras (from tensorflow.keras.models import Sequential, from tensorflow.keras.layers import Dense, Dropout, Conv2D, MaxPooling2D, Flatten, from tensorflow.keras.preprocessing.image import ImageDataGenerator, from tensorflow.keras.applications import VGG16): sebagai high-level API untuk membangun dan melatih model deep learning.
Matplotlib (import matplotlib.pyplot as plt): untuk visualisasi data dan plot grafik.
ImageDataGenerator (from tensorflow.keras.preprocessing.image import ImageDataGenerator): untuk melakukan augmentasi gambar pada saat pelatihan model.
VGG16 (from tensorflow.keras.applications import VGG16): sebagai pre-trained model yang di-import ke dalam arsitektur model yang dibangun.
NumPy (import numpy as np): untuk operasi numerik pada data array.
```
## Train & Validation Visual

<img src="output.png" >

## Final Ouput with multi-output

<img src="final-output.png" >
