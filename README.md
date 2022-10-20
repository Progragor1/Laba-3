# АНАЛИЗ ДАННЫХ И ИСКУССТВЕННЫЙ ИНТЕЛЛЕКТ [in GameDev]
Отчет по лабораторной работе №3 выполнил:
- Султанов Егор Альбертович
- РИ-210948

Отметка о выполнении заданий:

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | 60 |
| Задание 2 | # | 20 |
| Задание 3 | # | 20 |

знак "*" - задание выполнено; знак "#" - задание не выполнено;

Работу проверили:
- к.т.н., доцент Денисов Д.В.
- к.э.н., доцент Панов М.А.
- ст. преп., Фадеев В.О.

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)


## Цель работы
Познакомиться с программными средствами для создания системы машиного обучение и ее интеграции в Unity.
## Задание 1
### Реализовать систему машиного обучения в связке Python - Google-Sheets - Unity.

#### Создайте новый пустой 3D проект на Unity.
![Wdwdna4qrV4](https://user-images.githubusercontent.com/91984484/196927165-0b70f4c1-05d9-49f9-9af2-e720d5f9c1f8.jpg)
#### Скачайте папку с ML агентом.
![j8jeco5jWOc](https://user-images.githubusercontent.com/91984484/196927344-71575d2a-ac17-40d2-ab86-96d9192b500a.jpg)
#### В созданный проект добавьте ML Agent, выбрав Window - Package Manager - Add Package from disk. Последовательно добавьте .json – файлы
![e_-dwb9fMtE](https://user-images.githubusercontent.com/91984484/196927460-cfeea5b3-4f6e-40df-929e-457d70e71931.jpg)
#### Далее пишем серию команд для создания и активации нового ML-агента, а также для скачивания необходимых библиотек
![mZjgYu5nVNE](https://user-images.githubusercontent.com/91984484/196927556-37e9139c-3cab-4750-a733-b4f0338c0a71.jpg)
#### Создайте на сцене плоскость, куб и сферу так, как показано на рисунке ниже. Создайте простой C# скрипт-файл и подключите его к сфере
![FTE00k21PMU](https://user-images.githubusercontent.com/91984484/196927869-b890e77e-de0c-4606-805e-32b5588ffe4a.jpg)


![YPxD9qhfU58](https://user-images.githubusercontent.com/91984484/196927919-3cf56faa-027f-4f04-9398-6b6c0a2e147e.jpg)
#### Объекту «сфера» добавить компоненты Rigidbody, Decision Requester, Behavior Parameters и настройте их так, как показано на рисунке ниже
![F1aIVI01EqQ](https://user-images.githubusercontent.com/91984484/196928053-9421cea6-8b1a-40f1-a826-21a6fc9d917a.jpg)
#### Сделайте 3, 9, 27 копий модели «Плоскость-Сфера-Куб», запустите симуляцию сцены и наблюдайте за результатом обучения модели.
![MBlejfgc8No](https://user-images.githubusercontent.com/91984484/196928438-d1e667d8-0eb4-4a35-b951-1687378628f5.jpg)
#### После завершения обучения проверьте работу модели.
![gbK1Q7AxPZc](https://user-images.githubusercontent.com/91984484/196928544-6eea9a18-8088-4320-b2ff-12bbf56cb101.jpg)

## Задание 2
### Реализовать запись в Google-табдицу набора данных, полученных с помощью линейной регрессии из лаб. работы №1.



## Задание 3
### Самостоятельно разработать сценарий воспроизведения звукового сопровождения в Unity в зависимости от изменения считанных данных в задании 2.

## Выводы
### В результате работы:



| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |

## Powered by

**BigDigital Team: Denisov | Fadeev | Panov**
