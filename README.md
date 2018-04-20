# [imageMe](http://www.imageme.xyz/)

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
> git clone https://github.com/deanSunny/imageme.git
```


### Step 2: Run imageMe

Run `imageme.py` from the root directory to serve from:

```bash
> cd /path/to/my/pics
> imageme.py
Processing .
Creating index file ./imageme.html
Processing ./photos
Creating index file ./photos/imageme.html
Processing ./photos/holiday
Creating index file ./photos/holiday/imageme.html
Processing ./photos/family
Creating index file ./photos/family/imageme.html
Processing ./super_secret_stay_out
Creating index file ./super_secret_stay_out/imageme.html
Your images are at http://127.0.0.1:8000/imageme.html
```

You can specify a port, just like you can with `SimpleHTTPServer`:

```bash
Port = 
Num = 
Dir = 
>$ python imageme.py -p Port -n Num -d Dir

```

## Browse and Enjoy

Hit the URL imageMe tells you in your browser, and have fun exploring.
