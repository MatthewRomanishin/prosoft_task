# Описание
train.ipynb - ноутбук с кодом для обучения модели  
inference.ipynb - ноутбук с кодом инференса и расчетом метрики `Accuracy` на тестовой выборке  
В папке `models` лежит обученная модель

# Данные:
Перед обучением сбалансировал данные, удалил "дубликаты".  
 - [train](https://drive.google.com/file/d/1p8Cus4HRUCWzXEom4F3Mctqr6TdDXPxN/view?usp=sharing)
 - [test](https://drive.google.com/file/d/1EPCeGAzj2fbGmQF3Nr0n4WmV2d-7ff5k/view?usp=sharing)
 
 Для обучения модели и инференса необходимо скачать данные и распаковать в директорию. Затем запустить `train.ipynb`  
 # Инференс
 Для инференса и расчета `Accuracy` необходимо запустить `inference.ipynb`  
 
 На тестовой выборке удалось достичь `Accuracy` = 0.72
