# STOPKY

 ```./stopky.exported -h
----------------------------------------------------
  -v|--version         ... print version
  --update-version     ... change the file version to now 
  -h|--help            ... help
  --export             ... join all files into one script
  -s                   ... time measurement START
  -c                   ... countdown time or seconds
  -w                   ... see watch
  -a                   ... set alarm
 ./stopky.exported  -a  10     -w      ... alarm in 10 seconds, watches mode
 ./stopky.exported  -a  6:35   -w      ... alarm at next 6:35,  watches mode
 ./stopky.exported  -a  6:35   -c      ... alarm at next 6:35, countdown
 ./stopky.exported  -a  6:35   -c      ... alarm at next 6:35, timer
                  in -c mode space removes alarm sound
-----------------------------------------------------
```

## howto export with bashmagick

```./stopky.exported --update-version; ./stopky.exported --export; cp ./stopky.exported.exported ~/```
