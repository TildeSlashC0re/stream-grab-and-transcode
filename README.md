# SGAT - StreamGrab And Transcode [1.0]

>A wrapper for ffmpeg and streamlink to grab your favorite streams live and encode them right after

## Installation

```bash
    git clone https://github.com/TildeSlashC0re/stream-grab-and-transcode.git;
    cd stream-grab-and-transcode;
    cp config.example config
    nano config # Provide, at minimum, $WORKDIR and $STREAM
```

## Dependencies

```bash
    sudo apt-get update; 
    sudo apt-get install python-pip ffmpeg;
    pip install streamlink
```

## Running 

```bash
    ./listener
```

## Exiting

    `CTRL` + `C`


## Cleaning Up Log Directory

```bash
    ./log/nuke-logs
```

