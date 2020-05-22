# FER_with_antispoofing
Данная программа написана на Python 3.6. Протестирована на  Windows 10.

Для запуска необходимо установить следующие модули:
  * imutils==0.5.3
  * Keras==2.3.1
  * Keras-Applications==1.0.8
  * Keras-Preprocessing==1.1.0
  * numpy==1.17.2
  * matplotlib==3.1.1
  * opencv-python==4.1.1.26
  * pandas==0.25.1
  * Pillow==6.1.0
  * scapy==2.4.3
  * scikit-image==0.15.0
  * scikit-learn==0.22
  * scipy==1.1.0
  * sklearn==0.0
  * tensorboard==1.14.0
  * tensorflow==1.14.0
  * tensorflow-estimator==1.14.0
  * tf==1.0.0
  * torch==1.2.0
  * torchvision==0.4.0
  * tqdm==4.36.1
  * transforms==0.1
  * utils==0.9.0
Все обученые модели уже загружены в архив, добавлять в директории ничего не требуется.
Для запуска программы в режиме демонстрации необходимо использовать файл liveness_demo.py
## Для запуска в режиме по умолчанию необходимо использовать команду liveness_demo.py --model liveness.model --le le.pickle --detector face_detector 
  Также доступны следующие аргументы
    optional arguments:
      -h, --help            show this help message and exit
      -m MODEL, --model MODEL
                            path to trained model
      -l LE, --le LE        path to label encoder
      -d DETECTOR, --detector DETECTOR
                            path to OpenCV's deep learning face detector
      -c CONFIDENCE, --confidence CONFIDENCE
                            minimum probability to filter weak detections
                            

