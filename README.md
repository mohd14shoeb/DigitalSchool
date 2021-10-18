# Digital School ("Электронная-школа")

## Описание:

Система "Электронная школа",

- 1.1.при переходе на страницу проекта в браузере откроется форма аутентификации (форма Регистрации/Авторизации(проверка логина и пароля));
- 1.2. после авторизации открывается форма со списком учеников с кнопками "Добавить" и "Удалить";
- 1.3. при нажатии на кнопку "Добавить" откроется форма добавления ученика, при сохранении ученик будет добавлен в список;
- 1.4. при нажатии на кнопку "Удалить", ученик будет удален из списка.

## Technologies Used:

- ReactJS
- NodeJS
- ExpressJs
- MySQL
- JavaScript
- HTML
- CSS

### Database:

2 tables:

- Users: Хранит данные преподавателей (users), {username, password}.
- Students: Хранит данные студентов (students), {name, surname, midterm, endterm, final, gpa}.

<br/>

---

## 1.Чтобы скачать с гитхаба проект запускаем команду:

### `git clone https://github.com/alibekbirlikbai/Digital-School-React-MySql-NodeJs.git`

<br/>

---

## 2.Запускаем Client:

### 2.1.Переходим в папку client:

### `cd client`

<br/>

### 2.2.Далее в терминале вводим команды:

### `npm install`

### `npm install react-couter-dom`

### `npm install axios`

<br/>

### 2.3.Для запуска react приложения вводим команду:

### `npm start`

<br/>

---

## 3.Запускаем Server:

### 3.1.Переходим в папку server:

### `cd server`

<br/>

### 3.2.Далее в терминале вводим команды:

### `npm install mysql express`

### `npm install cors`

<br/>

### 3.3.Для запуска сервера вводим команду:

### `node .\index.js`

<br/>

---

## 4.Ждём, когда запуститься сервер. После запуска сервера, заходим в браузере по адресу:

### `http://localhost:3000/`

<br/>

### 4.1.Видим форму Аутентификации. Далее заходим в 'Registration' по адресу:

### `http://localhost:3000/registration-page`

<br/>

### 4.2.Регистрируемся, нажимаем на 'Registration' и попадаем на страницу списка студентов ('List of Students') по адресу:

### `http://localhost:3000/student-list`

<br/>

### 4.3.Далее если мы хотим `"Добавить"` нового студента мы должны нажать на кнопку 'Add new Student', тогда нас перенаправит на страницу 'Add new Student' по адресу:

### `http://localhost:3000/add-student`

<br/>

### 4.4.Заполняем анкету, нажимаем на кнопку 'Add', после чего нас занова перенаправит на страницу 'List of Students' с обновленной таблицей студентов.

<br/>

### 4.5.На странице 'List of Students', также можно `"Удалить"` данные определенного Студента нажав на кнопку 'Delete'(красная).

<br/>

### 4.6.Также на странице 'List of Students', можно выйти из аккаунта нажав на кнопку 'logout', после чего нас переноправит обратно на главную страницу Аутентификации.

### 4.7.Теперь мы можем авторизоваться с помощью введенных нами {username} и {password} при Регистрации.