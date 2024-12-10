# Проект. Методы защиты от фишинга, при помощи проверки доменного имени"

Для запуска необходимо скачать этот репозиторий на свой компьютер. Для этого необходимо на странице репозитория найти зеленую кнопку 'Code':

![code](https://github.com/AmandaYang679/Fishing-website--clone-)
<br>
Нажать на эту кнопку и выбрать 'Download ZIP':

![download](https://github.com/AmandaYang679/Fishing-website--clone-/archive/refs/heads/main.zip)

Распаковываем скаченный архив.

Теперь необходимо открыть командную сторку:
* Для Linux: открываем терминал.
* Для Windows: переходим в Поиск и набираем там 'командная строка'.

Далее переходим в разархивированную папку лабораторной работы:
```
cd 'путь до папки с лабораторной работы'
```

Убедитесь, что у Вас установлен python v3.6 и выше (если его нет или версия слишком старая, необходимо установить или обновить до версии 3.6 и выше):
* Для Linux
```
python3 --version
```
* Для Windows
```
python --version
```
Cоздаем и запускаем в ней venv (виртуальное окружение python):
* Для Linux
```
python3 -m venv myenv
source myenv/bin/activate
```
* Для Windows
```
python -m venv myenv
myenv\Scripts\activate
```
После устанавливаем все необходимые для python пакеты:
```
pip install -r requirements.txt
```
Запускаем сервер Django:
```
python manage.py runserver
```
Сервер Django по стандарту запускается по адресу http://127.0.0.1:8000/. Чтобы остановить работу сервера необходимо нажать комбинацию клавиш Ctrl+C.
