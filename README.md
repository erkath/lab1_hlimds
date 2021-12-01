# lab1_hlimds

Лабораторная работа 1 по курсу "Высокопроизводительные вычисления"

Реализация нейронной сети MobileNet с использованием Raspberry PI. 
Нейронная сеть распознаёт людей и другие объекты; написана с использованием opencv 3.4.1 и python 3.
Нейронная сеть разработана на основе проекта https://github.com/djmv/MobilNet_SSD_opencv

```Mobilenet_ssd_python.py```: 
Example take video file or videocamera as input. 

```sample_img.py```: 
Take a image as input. If don't load an image by default load img.jpeg 

## Run scripts
```sh
$ python3 mobilenet_ssd_python.py --[params] 
```
If no load params take video input value by default 

```sh
$ python3 sample_img.py --[params] 
```
If no load params take Image by default 

