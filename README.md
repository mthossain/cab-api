# Cab Trip Data - API
This API gives access to know that how many trips a particular cab (medallion) has made given a particular pickup date.

Full API Documentation is available on API's homepage.

[image]

## Requirements
### Used Packages
Please install these packages if you do not have them already.

* Python Flask: `pip install Flask`

* Official MySQL Connector: `pip install mysql-connector`

* Python Flask-Caching (Extension of the Flask-Cache): `pip install flask-caching`

### Modify MySQL Database Details
Please open `api.py` with a text editor and change local Database Details to your own local database.

```python
#--------------------------------------
#Database Details. Please modify this:
mysql_password = "ab12345678!"
database_name = "cab_data"
#--------------------------------------
```

## Screenshots
