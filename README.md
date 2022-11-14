# Blog Flask
The objective of this project is to further deepen the concepts of flask by developing a blog. 

## **Project Structure**
      └── to-do-list-flask
            ├── app.py
            ├── database
            │   └── blog.db
            ├── Dockerfile
            ├── README.md
            ├── requirements.txt
            ├── static
            │   └── style.css
            └── templates
                ├── agregar.html
                ├── inicio.html
                └── layout.html

`1.1. app.py` : This file was coded to flask and its main functions.

`1.2. database/` : This folder contain the database we are going to use.

`1.3. static/` : This folder contains the static files that we are going to use as for example the css.

`1.4. templates/` : This folder contains pages that are made with html.

`1.5. Dockefile` : Also, little to say about this container 



## **Installation**

You can use `Docker` to easily install all the needed packages and libraries.

```bash
$ docker build -t blog-flask -f Dockerfile .
```    

### Run Docker

```bash
$ docker run -d -p 5000:5000 blog-flask
```    


