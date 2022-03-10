# 1. Ссылка на google colab ноутбук

https://colab.research.google.com/drive/101o156NISl8vmG8Yl3P9RYaZhXE2qlzN?usp=sharing

# 2. FastQC

## ENCFF001FEM

![Снимок экрана 2022-03-10 в 20 04 49](https://user-images.githubusercontent.com/93208971/157716922-947e0a79-be33-4ff9-b53c-ba26cb18906e.png)

Здесь на лицо ошибка в Per tile sequence quality, уместно поработать с данными и сделать подрезание чтений:

До  | После |
--- | --- | 
![Снимок экрана 2022-03-10 в 20 05 31](https://user-images.githubusercontent.com/93208971/157717155-db58b2c3-fd1e-403b-90e8-5373b109eae2.png) | ![Снимок экрана 2022-03-10 в 20 05 43](https://user-images.githubusercontent.com/93208971/157717255-b825aa0f-f471-4713-9a81-9b5bfb6ee556.png) 

## ENCFF001FEP и ENCFF001FFI

Тут с данными все окей,  по все необходимым фильтрам качество приемлимое:  

ENCFF001FEP | ENCFF001FFI
--- | --- 
![Снимок экрана 2022-03-10 в 20 17 14](https://user-images.githubusercontent.com/93208971/157718819-25b74401-97df-4b46-b7d1-753af1b94d2d.png) |![Снимок экрана 2022-03-10 в 20 19 11](https://user-images.githubusercontent.com/93208971/157719121-7f3a9c00-97fe-4689-99ef-dba70f09af46.png)
![Снимок экрана 2022-03-10 в 20 21 39](https://user-images.githubusercontent.com/93208971/157719509-096b516d-1868-4ec0-84d0-72a6ac462d0e.png) | ![Снимок экрана 2022-03-10 в 20 21 14](https://user-images.githubusercontent.com/93208971/157719543-9993aaa2-2273-4aa2-b19b-8ea66fa5d427.png)

Все 4 полные отчета-htlm в дирертории /reports


# 3. Таблица со статистикой 

Образец | ENCFF001FEM | ENCFF001FEP | ENCFF001FFI | 
--- | --- | --- | --- |
Reads total | 14360898 | 25719182 | 18390264 | 
Unique reads aligned | 454893 | 839114  | 821433 | 
Non-unique reads aligned | 719806 | 1582901 | 2280908 | 
Not aligned | 13186199 | 23297167 | 15287923 | 

P.S Вычисления в google colab ноутбук

# 4. Картинки с диаграммой Венна
Диаграммы Венна | 
--- |
![Снимок экрана 2022-03-10 в 19 39 26](https://user-images.githubusercontent.com/93208971/157711535-2745e07e-fc04-470e-8962-49e6832088e5.png)|
![Снимок экрана 2022-03-10 в 19 39 43](https://user-images.githubusercontent.com/93208971/157711543-47090c9b-dc3c-4374-a0bd-6adfe55587c9.png)|
![Снимок экрана 2022-03-10 в 19 39 57](https://user-images.githubusercontent.com/93208971/157711545-59799184-a792-4e78-a85f-a649af5902ed.png)|
![Снимок экрана 2022-03-10 в 19 40 11](https://user-images.githubusercontent.com/93208971/157711549-5bd90c53-e717-417f-ac62-46775d34c971.png)|

Все 4 pdf файла в репозитории /images

# 5. Бонусное задание

Гистоновая метка H3K4me3 распределение из задания:
![Снимок экрана 2022-03-10 в 23 18 26](https://user-images.githubusercontent.com/93208971/157747725-dc00f023-5fe2-4c50-b336-1a97b669e21b.png)
В целом мы можно наблюдать соответсвие данных на графике с эксперементальнами. Распределение явно отличимо на фоне других в примере из задания: резкий рост значении с формурование вершины в первой третий график, и дальнейшее уменьшении значении распределения. Получившиеся в ходе работы данные ниже:

![result](https://user-images.githubusercontent.com/93208971/157746644-8f6b2cd5-5f9e-4ca2-a7fd-80d713b265ce.png)| ![result_2](https://user-images.githubusercontent.com/93208971/157746682-8b13805f-253f-41ab-84c3-8c489f3b69f2.png)| 
--- | --- | 
