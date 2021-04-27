### Setup

Clone or Fork this repo (we can actually talk about what workflow makes the most sense)

Install requirements

```
pip install -r requirements.txt
```

Download the [example file](https://drive.google.com/file/d/1IqPv38rCQEyJjuclUftX3_5Iix_rAATO/view?usp=sharing) from Alexandra (github doesn't like files bigger than 100mb)

The multi-viewer can take in additional camera views but they have to be synced to your main video start time.

 I'm still getting some bugs in plotting functionality ironed out but again data streams  have to be synced to main video start time. 

The multi viewer can also take in a callback function that is run every time you add a notation. This is what David was using for syncing multiple users notes. 
