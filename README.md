# TestWebsite
TestWebsite is a small project that sets up a locally hosted server on port 8000.
Running the script with `python TestWebsite.py` will launch the server.
Running the script with `python TestWebsite.py webaddress` will download the source at webaddress and wipe the existing index.htm and replace it with downloaded source. The server will then launch.

Now develop scraping software to access `localhost:8000` rather than `webaddress` to avoid unnecessary load on `webaddress` servers
