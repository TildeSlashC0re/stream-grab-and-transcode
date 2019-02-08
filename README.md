# SGAT - StreamGrab And Transcode [1.1.2]

>A wrapper for ffmpeg and streamlink to grab your favorite streams live and encode them right after

**Note:** a more thorough documentation is scheduled for **soon™**
### If you ran SGAT 1.1.1 and below, **please update your config!**

## Installation

```bash
    git clone https://github.com/TildeSlashC0re/stream-grab-and-transcode.git;
    cd stream-grab-and-transcode;
    cat config.example > config;
    nano config # Provide, at minimum(!), $WORKDIR

    # Optionally you can also
    nano config.streamlink
```

## Dependencies

```bash
    sudo apt-get update; 
    sudo apt-get install python-pip ffmpeg;
    pip install streamlink
```

### Optional Dependencies
```bash
    # if you defined $APPRISE_HOOK_TARGET in your config you need to 
    pip install apprise
```

## Running 

```bash
    ./listener

    # OR
    ./listener <url>
```

## Exiting

```bash
    CTRL + C
```

## Cleaning Up Log Directory

```bash
    ./log/nuke-logs
```

