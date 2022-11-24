# disease-prediction system
This a disease prediction website that you input your symptops and it predicts the disease you are suffering from.
Developed by django and model trained by Naive Bayes classifier

How to Run this Django project
First make sure PostgreSQL and pgadmin4 is install in your system. then you have to manually create a DataBase instance on PostgreSQL named "predico", better use PgAdmin for that. make a new environment(recommended) and run...

- Run pip install dependencies
    django==3.0.3
	  joblib==0.14.1
	  scikit-learn==0.21.3
	  psycopg2==2.8.4
- Run python manage.py makemigrations
- Run python manage.py migrate
- Run python manage.py runserver
- Navigate to http://127.0.0.1:8000/ in your browser
