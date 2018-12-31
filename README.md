# SGAT - StreamGrab And Transcode [1.0.2]

>A wrapper for ffmpeg and streamlink to grab your favorite streams live and encode them right after

## Installation

```bash
    git clone https://github.com/TildeSlashC0re/stream-grab-and-transcode.git;
    cd stream-grab-and-transcode;
    cat config.example > config;
    nano config # Provide, at minimum, $WORKDIR

    # Optionally you can also
    nano config.streamlink
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

```bash
    CTRL + C
```

## Cleaning Up Log Directory

```bash
    ./log/nuke-logs
```

