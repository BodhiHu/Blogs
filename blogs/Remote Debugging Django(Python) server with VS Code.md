# Remote Debugging Django(python) server with VS Code

**1 start server with debug enabled:**
```
$ # install the python debug package if not yet
$ pip install debugpy
$ # start server with debugging enabled
$ python3 -m debugpy --listen 0.0.0.0:5678 ./manage.py runserver 0.0.0.0:8000
```

**2 setup vscode remote debug config**

=> ```Ctrl+Shift+D``` to bring up "Run and Debug" view
<br/>
=> "Add Configuration"
<br/>
=> add below to ```./.vscode/launch.json``` and save:
```
    {
      "name": "Python: Remote Attach",
      "type": "python",
      "request": "attach",
      "connect": {
        // NOTE: replace to your server host
        "host": "172.24.187.245",
        "port": 5678
      }
    }
```
<br/>

Now we can start remote debugging:

<img src="../imgs/Remote%20Debugging%20With%20Django(python)%20with%20VS%20Code%20screen%20capture.jpg" />
