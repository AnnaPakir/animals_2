# Начальная настройка весов сверточных нейронных сетей

Код [link](https://github.com/AnnaPakir/animals_2/blob/main/animals_2_%D0%9F%D1%80%D0%B5%D0%B4%D0%BE%D0%B1%D1%83%D1%87%D0%B5%D0%BD%D0%B8%D0%B5_.ipynb)

Отчет [link](https://github.com/AnnaPakir/animals_2/blob/main/%D0%9B%D0%B0%D0%B1.%D1%80%D0%B0%D0%B1%20%E2%84%965.pdf)

В данной работе был произведен эксперимент по предобучению сверточных неронных сетей. Были использованы три варианта начальной настройки: автоэнкодер, SimCLR, k-means. В качестве основной модели была использована упрощенная модель из  работы [link](https://github.com/AnnaPakir/animals)

Ссылка на данные в Kaggle: [link](https://www.kaggle.com/datasets/alessiocorrado99/animals10/data)

![plot](https://github.com/AnnaPakir/animals/blob/main/animals_png.png)

Было создано три варианта предобучения сверточных неронных сетей

![plot](https://github.com/AnnaPakir/animals_2/blob/main/result_animals.png)

Лучшим было признано предобучение с помощью автоэкодера, метрика выроста почти на 0.03
Данная модель может быть доработана посредством доработки обучающей увеличения эпох обучения.
