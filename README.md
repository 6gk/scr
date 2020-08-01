# rec(ord)

Personal recording script

```
Options
 -s    save the recording
 -h    display this message
 -c    skip the confirm start message
 -p  ? save and load settings from profile
 -r  ? framerate
 -b  ? force bitrate  (in MB)
 -m  ? force method   (crud, boox, display)
 -d  ? force display
 -n    disable NVENC for unsupported nvidia cards
 -a    Record desktop audio

? = Option requires another argument

Variables
 REC_DIR: If unset, saves in the current directory
 REC_FILE: If unset, saves as 'rec-$(date '+%Y-%m-%d_%H-%M-%S').mp4'

Dependencies
 github.com/pockata/mmutils | getting info about displays
AND / OR
 github.com/ix/crud         | selecting an area
 github.com/BanchouBoo/boox | selecting an area

 ffmpeg
 dmenu (or a clone) (with the binary name 'menu')
```
