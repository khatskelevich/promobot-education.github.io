# Прямое управление Rooky. Подготовка и запуск на Ubuntu 16.04

❗ Рекомендуется использовать версию Python **не ниже 3.5** (встроена в систему Ubuntu 16.04).

Узнать версию **Python** можно командой в терминале:
```sh
python3 --version
```

## Подготовка к работе
* Открыть терминал: **Ctrl + Alt + T**
* Написать следующие команды:
  ```sh
  cd ~
  git clone https://github.com/Promobot-education/Rooky.git
  cd ./Rooky
  chmod +x ./install.sh
  ```
* Установить требуемые зависимости и компоненты:
  ```bash
  ./install.sh
  ```
* Библиотеки готовы к использованию
* **Подготовка для прямого управления закончена.**

## Запуск примеров на языке Python
* Подключить манипулятор Rooky к ПК
* Открыть терминал: **Ctrl + Alt + T**
* Перейти в директорию с примером:
  ```sh
  cd ~/Rooky/python/examples
  ```
* Запустить пример:
  ```
  python arm_test.py
  ```  
  или  
  ```
  python3 arm_test_2.py
  ``` 


## Запуск примеров на языке С++
* Открыть терминал: **Ctrl + Alt + T**
* Перейти в дирректорию с **С++** библиотекой
```bash
cd ./Rooky/cpp
```
* Скомпилировать исходный код примеров
```bash
make
```
* Перейти в дирректорию со скомпилированными примерами
```bash
cd ./build
```
* Запустить пример
```bash
./read_servos
```