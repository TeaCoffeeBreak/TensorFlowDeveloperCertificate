# ImageGenerator

https://github.com/lmoroney/dlaicourse/blob/master/Course%201%20-%20Part%208%20-%20Lesson%202%20-%20Notebook.ipynb

https://github.com/lmoroney/dlaicourse/blob/master/Course%201%20-%20Part%208%20-%20Lesson%203%20-%20Notebook.ipynb

https://github.com/lmoroney/dlaicourse/blob/master/Course%201%20-%20Part%208%20-%20Lesson%204%20-%20Notebook.ipynb


https://www.tensorflow.org/api_docs/python/tf/keras/preprocessing/image/ImageDataGenerator

```
from tensorflow.keras.preprocessing.image
import ImageDataGenerator


# ------- Training ----------------------------------
train_dategen = ImageDataGenerator(rescale=1./255)

train_generator = train_datagen.flow_from_directory(
          train_dir,
          target_size=(300,300),
          batch_size=128,
          class_mode='binary')
          
# ------- Test ----------------------------------

test_dategen = ImageDataGenerator(rescale=1./255)

validation_generator = test_dategen.flow_from_directory(
          validation_dir,
          target_size=(300,300),
          batch_size=32,
          class_mode='binary')


```
