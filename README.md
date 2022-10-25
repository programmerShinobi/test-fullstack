<h1 align="center">Test Fullstack (Frontend & Backend)</h1>
<p>Test Fullstack - Faqih Pratama Muhti</p>

## Author
Laravel 8 Articles created by :

- Github : <a href="https://github.com/programmerShinobi"> Faqih Pratama Muhti | programmerShinobi </a>

## Feature 
- CRUD RESTfull-API Posts
- CRUD Posts

## Run This Apps
- Download the master branch in terminal
	``` 
    git clone git@github.com:programmerShinobi/test-fullstack.git
    ```
- Install the composer dependencies in terminal
	```
    composer install
    ```
- Make a file .env from .env.example and setting your config & create database name :  article
    ```
    //...
    APP_URL=http://127.0.0.1:8000
    //...
    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=article
    DB_USERNAME=root
    DB_PASSWORD=
    //...
    ```
- Dont forget generate key from Laravel artisan in terminal
	```
    php artisan key:generate
    ```
- Run composer update in terminal
	```
    composer update
    ```
- Run Seed and faker in terminal
	```
    php artisan migrate:fresh --seed
    ```
- Run serve in terminal
    ```
    php artisan serve
    ```
- Run apps in web browser
	```
    http://127.0.0.1:8000
    ```
- Run RESTfull API in API testing tool
    ```
    http://127.0.0.1:8000/api/...
    ```
- If you run RESTfull API in testing tool using Postman, just download the file from <a href="https://drive.google.com/drive/folders/1Gfjv_3_Mh_y_-47TqjADihEx8vzuzyuI?usp=sharing">**this google drive link**</a>. And then import the file into your API testing tool using Postman

- If you test Backend (REST API) : Create post with method ```POST``` & Run REST API in testing tool
    ```
    http://127.0.0.1:8000/api/article
    ```
- If you test Backend (REST API) : Display all posts with method ```GET``` & Run REST API in testing tool
    ```
    http://127.0.0.1:8000/api/article
    ```
- If you test Backend (REST API) : Show detail post with method ```GET``` & Run REST API in testing tool
    ```
    http://127.0.0.1:8000/api/article/{id}
    ```
- If you test Backend (REST API) : Update post with method ```PUT``` & Run REST API in testing tool
    ```
    http://127.0.0.1:8000/api/article/{id}
    ```
- If you test Backend (REST API) : Delete post with method ```DELETE``` & Run REST API in testing tool
    ```
    http://127.0.0.1:8000/api/article/{id}
    ```

## If you have some suggestion ||~
Just Contact Me At :
- Email     : <a href="mailto:faqihpratamamuhti@gmail.com">faqihpratamamuhti@gmail.com</a>
- LinkedIn  : <a href="https://www.linkedin.com/in/faqih-pratama-muhti-9a75a2130/">Faqih Pratama Muhti</a>
