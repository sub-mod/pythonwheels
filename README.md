
```
git clone https://github.com/sub-mod/pythonwheels.git  
cd pythonwheels  
```

```
docker run -it -u 0 -v $(pwd):/input:Z --privileged submod/tfdemo2019_1 /bin/bash
cd /input
pip install pytz 
pip install requests
make generate
```

in new terminal from pythonwheels folder
```python3 -m http.server 8000```