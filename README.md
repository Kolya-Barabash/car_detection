# car_detection
ОБЩАЯ ИНФОРМАЦИЯ:  
Данный репозиторий содержит два файла: .exe - программа, .xml - каскадный классификатор.  
Данная программа позволяет детектировать автомобили на изображении, а также видео. Программа была реализована на языке C++ с использованием библиотеки OpenCV версии 3.1.0. Графическая оболочка была сделана при помощи Windows Forms.    
Приложение было протестировано на Windows 7/8.1/10 (x64) и работало корректно.

КАК ПОЛЬЗОВАТЬСЯ:  
Загрузите все фалы.  
Скачайте два .dll файла: opencv_world310.dll, opencv_ffmpeg310_64.dll.  Скачать можно по ссылке https://drive.google.com/drive/folders/0B_fePdNZl0eSTkJaNlVVMng2V0k   или же с официального сайта OpenCV http://opencv.org/  
Соберите все файлы в одну папку.   
Зупустите приложение.  

РЕЗУЛЬТАТЫ:  
Программа показывает хорошие результаты на тестовой базе: http://cogcomp.cs.illinois.edu/Data/Car/   
Я не могу гарантировать великолепных результатов на других изображениях.  
Для лучших результатов размер автомобиля на картинке должен быть не меннее 20x20px., а также лучше использовать тестовое изображение размером 300x250px.. Вы можете использовать тестовые изображения больших размеров, но в процессе работы программы оно будет уменьшено до 300x250px., в результате чего изображение будет искажено и детектировать автомобиль уже будет сложно.  
Размер видео не искажается, детектирование происходит на исходном размере.
