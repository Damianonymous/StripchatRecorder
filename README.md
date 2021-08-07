# StripchatRecorder 

All credits to @beaston02 and @ahsand97

This is script to automate the recording of public webcam shows from stripchat.com. 

## Requirements

Requires python3.5 or newer. You can grab python3.5.2 from https://www.python.org/downloads/release/python-352/

to install required modules, run:
```
python3.5 -m pip install streamlink bs4 lxml gevent
```


Edit the config file (config.conf) to point to the directory you want to record to, where your "wanted" file is located, which genders, and the interval between checks (in seconds)

Add models to the "wanted.txt" file (only one model per line). The model should match the models name in their chatrooms URL (https://stripchat.com/{modelname}/). T clarify this, it should only be the "modelname" portion, not the entire url.
