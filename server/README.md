# Getting Started on the Server Side
If you are using windows, you may need to use MINGW/Git Bash or any other command line that can run linux commands which can be downloaded here. https://git-scm.com/downloads
1. Set up a Python virtual environment and install the required packages by running the setup script:
```shell
chmod +x setup.sh
./setup.sh
```

2. Start up the virtual environment
```shell
source .venv/bin/activate

If this does not work try .venv/Scripts/activate or go into the server directory and type the directory the activate folder is located in.
```

2. Boot up the server by running the main script
```bash
python main.py
```

3. You should now have a python server running in the client if you navigate to port 8000 (type localhost:8000) in your browser. This port will make calls to port 8000 which you just set up to host the server.

4. If you run in to any CORS issues, restart your browser completely as caching might mess things up.

5. When you are done, deactivate the venv
```bash
deactivate
```
