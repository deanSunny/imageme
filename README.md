imageMe is a super simple image gallery server.

Think `python -m SimpleHTTPServer` for pictures.

![](http://www.imageme.xyz/images/screenshots/image_index.png)

## Super Duper Easy One Line Usage

To run the image server on port 8000:

## Manual Usage

### Step 1: Get the File

Get hold of a copy of `imageme.py`. For _really_ easy use put it in your `PATH`.

You could clone this repo:

```bash
> git clone git@git.tuputech.com:DiHuang/ImageMe.git 
```


### Step 2: Run imageMe

Run `imageme.py` from the root directory to serve from:

```bash
> cd /path/to/my/pics
> imageme.py
Processing .
Creating index file ./index.html
Processing ./photos
Creating index file ./photos/index.html
Processing ./photos/holiday
Creating index file ./photos/holiday/index.html
Processing ./photos/family
Creating index file ./photos/family/index.html
Processing ./super_secret_stay_out
Creating index file ./super_secret_stay_out/index.html
Your images are at http://127.0.0.1:8000/index.html
```

You can specify a port, just like you can with `SimpleHTTPServer`:

```bash
Port = 8008 (default: 8000)
Num = 5 (default: 3)
Dir = /path/to/image dir (default: ./)
>$ python imageme.py -p Port -n Num -d Dir

```

---
##### New feature
---
[Pip config](https://git.tuputech.com/FRG/hz_docs/blob/master/dev_env/hz_pypi_config.md)

```pip install imageme --user```

```bash
>$ imageme -p Port -n Num -d Dir
```

## Browse and Enjoy

Hit the URL imageMe tells you in your browser, and have fun exploring.
