# Cab Trip Data - API
This API gives access to know that how many trips a particular cab (medallion) has made given a particular pickup date.

Full API Documentation is available on API's homepage.


## Requirements
### Used Packages
Please install these packages if you do not have them already.

* Python Flask: `pip install Flask`

* Official MySQL Connector: `pip install mysql-connector`

* Python Flask-Caching (Extension of Flask-Cache): `pip install flask-caching`

### Modify MySQL Database Details
Please open `api.py` with a text editor and change local Database Details to your own local database.

```python
#--------------------------------------
#Database Details. Please modify this:
mysql_password = "YOUR_MYSQL_PASSWORD"
database_name = "YOUR_DATABASE_NAME"
#--------------------------------------
```

## Screenshots
### Homepage
![Homepage](https://i.postimg.cc/T1FZ3wkN/Screen-Shot-2019-01-19-at-9-12-58-pm.png)
### JSON Output
![JSON Output](https://i.postimg.cc/L4WdTCHk/Screen-Shot-2019-01-19-at-9-17-16-pm.png)
### TEXT Output
![TEXT Output](https://i.postimg.cc/bNS7FxJ7/Screen-Shot-2019-01-19-at-9-17-27-pm.png)
