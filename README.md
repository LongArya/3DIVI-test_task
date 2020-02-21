# 3DIVI-test_task
Тестовое задание для школы компьютерного зрения 3DIVI (Зима 2020)
Данная программа состоит из двух частей
1) generate:

  Генерирует координаты треугольника на изображении 500 * 500 
  
  Производит зашумление каждого пикселя с вероятностью P
  
  Генерирует изображение в формате pgm
  
  
2) restore:

  Восстанавливает координаты треугольника по зашумленному изображению и записывает в файл output.txt
  
  
  

Программа запускается из командной строки

python3 solver.py -generate P

python3 solver.py -restore image.pgm


Как видно первый аргумент это -generate/-restore — режим работы программы

Второй аргумент P для -generate — вероятность зашумления / image.pgm для -restore — путь изображения для восстановления
