# Test_task_c++
## Инструкция по компиляции
1) Должна быть установлена среда Cygwin
2) Если среда установлена только что, запустите программу установки Cygwin (setup.exe) и в диалоге Select Packages выберите следующие пакеты из категории Devel:
- gcc-g++: GNU Compiler Collection (C++)
- gdb: The GNU debugger
3) После установки, нужно запустить Cygwin Terminal и перейти в папку, в которой должен находиться файл с исходным кодом.
  Например, можно создать в домашней директории папкe progcpp, а в ней папку prog:
  ```
  $ mkdir progcpp
  $ cd ~/progcpp
  $ mkdir prog
  $ cd ~/clearning/helloworld
```
 В эту папку следует поместить файл main.cpp и текстовый файл, содержащий входные данные (по условию, он должен заканчиваться переносом строки)

4) Запускаем компилятор:
 ```
  $ g++ -o task.exe main.cpp
```
5) Запускаем программу с названием текстового файла первым аргументом при запуске программы.
  Пример:
```
  $ ./task.exe test_file.txt
```

P.S. Примеры тестовых файлов и консольный вывод содержатся в файле Тестовые_данные.docx






