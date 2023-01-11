# atoti Project


![image](https://user-images.githubusercontent.com/115105125/211676747-fa370022-5c74-43e7-b915-07916d6e2312.png)


Atoti is a free Python BI analytics platform for Data Analysts, Data Scientists & Business Users to analyze their data into business KPIs.
It is a BI analytics platform combining a python library and a web application.
Atoti was launched in 2020 by ActiveViam (Paris).



## Commands

To load the project:

- Built image:

```bash
docker build -t atoti .
```

- Create a volume:

```bash
docker volume create --name vol-atoti
```

- Run contener:

```bash
docker run --publish 8800:80 --volume vol-atoti atoti
```

- Access to application: [http://localhost:8800/#/](http://localhost:8800/#/)



## Usage

To get an overview ot Atoti. You can play with visualisations using preloaded data:

![image](https://user-images.githubusercontent.com/115105125/211925729-3449582e-90ad-4bdf-b7e0-8c4f9c3c4aeb.png)

