# uvicorn-servers-exception
Temporary repo to demo issues resolved by [uvicorn/pull/1845](https://github.com/encode/uvicorn/pull/1845)


## Steps
1) Pull down this repo
2) `pip install -r requirements.txt`
3) `mkdocs serve`
4) `python test.py`
5) This should have generated a `AttributeError: 'Server' object has no attribute 'servers'`
