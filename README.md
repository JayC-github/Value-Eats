# capstoneproject-comp3900-h13a-pass

## requirements
- Flask 2.0.1
- Python 3.8.2
- Flask_SQLAlchemy 2.5.1
- SQLAlchemy 1.4.19
- pytest 6.2.4
- Flask 2.0.1
- Werkzeug 2.0.1
- PyJWT 2.1.0

Note that any other python3 version should work, and lower version of Flask could work as well

## run the server on localhost
### install requirements
```
pip3 install -r requirements.txt
```

### run
1. go to the root directory
2. load some data to database:
```
python3 load_data.py
```
if sqlalchemy.exc.OperationalError: (sqlite3.OperationalError) disk I/O error
*remove the existing database file from the backend directory.
```
rm valueEats.db
rm valueEats.db-journal
```
3. set FLASK_APP variable, run this on mac/Linux terminal
```
export FLASK_APP=run.py
```
4. run:
```
flask run
```
if port 5000 is being used, use the other ports
eg:
```
flask run -p 5001
```
or set flask run port variable by
```
export FLASK_RUN_PORT=5001
```

### Eateries and Diners account
Some eateries, diners, vouchers and reviews are already loaded into the database via `python3 load_data.py` in previous step.
You can register new diners or eateries by yourself, but there won't be any vouchers, reviews or booking for a new user.
Or you can check some preloaded acounts, login with following account:
| Eatery email       | Eatery password | Diner email     | Diner password |
|--------------------|-----------------|-----------------|----------------|
| 00000001@gmail.com | 12345678        | 00000001@qq.com | 12345678       |
| 00000002@gmail.com | 12345678        | 00000002@qq.com | 12345678       |
| 00000003@gmail.com | 12345678        | 00000003@qq.com | 12345678       |
| 00000004@gmail.com | 12345678        | 00000004@qq.com | 12345678       |
| 00000005@gmail.com | 12345678        | 00000005@qq.com | 12345678       |
| 00000006@gmail.com | 12345678        | 00000006@qq.com | 12345678       |
| 00000007@gmail.com | 12345678        | 00000007@qq.com | 12345678       |
| 00000008@gmail.com | 12345678        | 00000008@qq.com | 12345678       |
| 00000009@gmail.com | 12345678        | 00000009@qq.com | 12345678       |
| 00000010@gmail.com | 12345678        | 00000010@qq.com | 12345678       |
| 00000011@gmail.com | 12345678        | 00000011@qq.com | 12345678       |
| 00000012@gmail.com | 12345678        | 00000012@qq.com | 12345678       |
| ...                | ...             | ...             | ...            |


![Report](report/01.png)
![Report](report/02.png)
![Report](report/03.png)
![Report](report/04.png)
![Report](report/05.png)
![Report](report/06.png)
![Report](report/07.png)
![Report](report/08.png)
![Report](report/09.png)
![Report](report/11.png)
![Report](report/12.png)
![Report](report/13.png)
![Report](report/14.png)
![Report](report/15.png)
![Report](report/16.png)
![Report](report/17.png)
![Report](report/18.png)
![Report](report/19.png)
![Report](report/20.png)
![Report](report/21.png)
![Report](report/22.png)
![Report](report/23.png)
![Report](report/24.png)
![Report](report/25.png)
![Report](report/26.png)
![Report](report/27.png)
![Report](report/28.png)
![Report](report/29.png)
![Report](report/30.png)
![Report](report/31.png)
![Report](report/32.png)
![Report](report/33.png)
