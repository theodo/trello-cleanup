# Trello Cleanup

When you have to many trello bords opened it is hard to know which one you can close or not.
With this little application you can list all the boards of your organizations and filter
opened, closed or inactive boards to close them.

**Be careful, this is a POC so use it at your own risks**

# How to install it?

Well this is a quite simple application build in plain old javascript. All you have to
do is open the ```trello.html``` page in your browser served by a server. You can use
the ```http.server``` module of Python3 for example:

```bash
$ python3 -m http.server
Serving HTTP on 0.0.0.0 port 8000 ...
```

Now the application is available on http://0.0.0.0:8000.
