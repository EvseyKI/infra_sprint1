# infra_sprint1
Kittygram — социальная сеть для обмена фотографиями любимых питомцев.
### Для запуска локально
1. Клонируем репозиторий и переходим в infra_sprint1/backend/
```
git clone git@github.com:EvseyKI/infra_sprint1.git
```
2. Создаем и активируем виртуальное окружение
```
python -m venv env
source venv/bin/activate
```
3. Устанавливаем необходимые зависимости из requirements.txt
```
python3 -m pip install --upgrade pip
pip install -r requirements.txt
```
4. Выполняем миграции
```
python manage.py migrate
```
5. Создаем пользователя
```
python manage.py createsuperuser
```
6. Запускаем проект
```
python manage.py runserver 0:8080
```
