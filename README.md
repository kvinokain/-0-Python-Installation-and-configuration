# Практическая работа №6. Знакомство с инструментальной средой программирования
## Цель работы - Установить и поработать с инструментальной средой программирования.

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=37C736&width=435&lines=%23+Let's+begin!;python+--version;%23+Python+%F0%9F%90%8D;apt+show+python3)](https://git.io/typing-svg)

## Установка и настройка Python

**Python** — это высокоуровневый язык программирования, который используется для разработки веб-приложений, автоматизации задач, анализа данных, машинного обучения и многого другого. Он известен своей простой и понятной синтаксической структурой, что делает его идеальным как для начинающих программистов, так и для профессионалов.

## 1. Где скачать Python
Python можно скачать с официального сайта: [python.org](https://www.python.org/downloads/). На этом сайте всегда доступны последние стабильные версии языка для различных операционных систем:

- **Windows**
- **macOS**
- **Linux**
  
А также документация, примеры и помощь по работе с языком программирования.

## 2. Как установить
**В примере показано, как установить Python на OS Windows x64** <br>
1. Зайдите на официальный сайт Python. <br>
   <img src="https://github.com/TeachKait20/NoneCode/blob/main/screenshots%20download+config%20Python/s1.jpg?raw=true">
 
2. Перейди на страницу загрузок и выбери подходящую версию для твоей операционной системы. Вы можете увидеть множество версий Python, такие как: 3.10, 3.11, 3.12 и последующие включают множество улучшений и новых возможностей. Скачайте установочный файл и запусти его.<br>
   <img src="https://github.com/TeachKait20/NoneCode/blob/main/screenshots%20download+config%20Python/s2.jpg?raw=true">
   
3. Во время установки убедись, что выбрана опция "Add Python to PATH", чтобы в дальнейшем можно было использовать Python из командной строки.  <br>
   <img src="https://github.com/TeachKait20/NoneCode/blob/main/screenshots%20download+config%20Python/s3.jpg?raw=true">

4. Дождитесь конца установки и закройте окно. <br>
   <img src="https://github.com/TeachKait20/NoneCode/blob/main/screenshots%20download+config%20Python/s4.jpg?raw=true">

Если всё проло успешно, то теперь у вас есть интерпретатор Python (Интерпретатор — это программа, которая выполняет команды, написанные на каком-то языке программирования.) и IDLE — это интегрированная среда разработки и обучения на языке Python.) <br>
   <img src="https://github.com/TeachKait20/NoneCode/blob/main/screenshots%20download+config%20Python/s5.jpg?raw=true">

## Работа без IDLE
Введите в разделе поиск Windows слово "python" и нажмите правой кнопкой мыши по найденной программе:

![image](https://github.com/user-attachments/assets/468cb6bd-038d-4f9a-b785-30166063afd9)

Нажмите на кнопку **перейти к расположению файла.** Затем еще раз найдите IDLE и нажмите по ней правой кнопкой мыши - **расположение файла.**

![image](https://github.com/user-attachments/assets/323a1c92-444b-4197-bcec-5d28cf873252)

Если вы все сделали верно - откроется папка с установленным языком программирования. 

![image](https://github.com/user-attachments/assets/5caded21-fb5f-4044-9dae-566e2156fbdc)

Теперь в эту папку необходимо загрузить файл с программой - вы можете написать свою или воспользоваться примером - https://disk.yandex.ru/i/6nV0Pst2UtAeVw

![image](https://github.com/user-attachments/assets/0aa91d9d-7aa3-47c3-98a5-bf1390828cba)

Теперь необходимо открыть программу powershell. Для этого нажмите правой кнопкой мыши по значку windows и нажмите на **powershell**

![image](https://github.com/user-attachments/assets/cd6a43e9-a362-4e40-b93f-65bf80832be8)

Копируем полный путь до папки из проводника Windows:

![image](https://github.com/user-attachments/assets/83354324-874a-4c20-bf23-92a00526da20)

Затем с помощью powershell вводим путь с командой cd. (Для того, чтобы "вставить" в powershell требуется нажать правой кнопкой мыши)

![image](https://github.com/user-attachments/assets/1c052e3b-53d9-472f-8ded-9eaaae36da1f)

Вводим в терминал - .\python.exe .\primer.py

![image](https://github.com/user-attachments/assets/3590306b-a9db-4884-bf8d-0acab5417fab)

Оцените уровень удобства такого подхода. Теперь попробуйте сделать это с помощью IDLE.

## 3. О IDLE
   
IDLE (Integrated Development and Learning Environment) — это простая среда разработки, которая поставляется вместе с Python. Она предназначена для написания, выполнения и отладки кода. IDLE включает в себя редактор кода с подсветкой синтаксиса и консоль Python для быстрого тестирования скриптов.

**Основные функции IDLE:**
- Подсветка синтаксиса.
- Автодополнение кода.
- Простой отладчик для проверки и отладки кода.
- Удобная консоль Python для выполнения команд в режиме реального времени.
- IDLE отлично подходит для начинающих, так как позволяет легко и быстро начать работать с Python без необходимости устанавливать сторонние IDE (например, PyCharm или Visual Studio Code, о них поговорим позже).

## 4. Запуск IDLE

*Запустите IDLE**:
   - На Windows: найдите "IDLE" в меню «Пуск» или просто введите «IDLE» в строке поиска.
   - На macOS: откройте Finder, перейдите в папку «Программы», найдите папку Python и запустите IDLE.
   - На Linux: запустите терминал и введите `idle3`, если он установлен.

2. **Откроется окно консоли Python Shell**:
   - В этом окне можно выполнять команды Python в интерактивном режиме.

4. **Создание нового файла**:
   - Чтобы начать писать код, выберите **File > New File** или нажмите `Ctrl + N` (Windows/Linux) или `Cmd + N` (macOS).
   
5. **Напишите свой код и запустите его**:
   - После написания кода выберите **Run > Run Module** или нажмите `F5`, чтобы выполнить программу.
   - Сохранения обязательны.
   
6. **Использование редактора кода**:
   - IDLE поддерживает подсветку синтаксиса, автодополнение и простую отладку, что делает его удобным для быстрого тестирования и разработки.

**Весь процесс IDLE** <br>
<img src="https://github.com/TeachKait20/NoneCode/blob/main/screenshots%20download+config%20Python/s6.gif?raw=true">


