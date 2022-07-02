# Бинарный классификатор <br>
## Исходные данные: <br>
![alt text](https://github.com/GermanYanchenko/ImageClass_binary/blob/main/image/data.png?raw=true)
<br>
Простая нейронная сеть из 4ех сверточных и 2ух полносвязных слоев. Оптимизатор - adam, лосс-функция - бинарная кросс-энтропия, метрика - тончность.<br>
История обучения 30 эпох: <br>
![alt text](https://github.com/GermanYanchenko/ImageClass_binary/blob/main/image/history.png?raw=true)<br>
Точность на тренировочных данных около 100%, что является признаком переобучения. Способы борьбы - использование более глубокой сети или увеличение исходных данных.
<br>
Предсказание обученной модели: <br>
![alt text](https://github.com/GermanYanchenko/ImageClass_binary/blob/main/image/predict.png?raw=true)
