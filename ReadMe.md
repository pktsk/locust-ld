## Installation steps
1. Install Python3
2. Install python virtual env
   ```
   python3 -m pip install --user virtualenv

   ```
3. Create a virtual env named: ldenv
```
python3 -m venv ldenv 
```
4. Activate env
```
source ldenv/bin/activate
```
5. Install locust package
```
pip3 install locust
```
6. Start the locust server

```
locust -f locust.py  
```
7. open ```http://0.0.0.0:8089 ``` on your browser

## Important Links 
* [Free Fake Api](https://jsonplaceholder.typicode.com)