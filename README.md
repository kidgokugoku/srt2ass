# subTools

 ```
usage: srt2ass.py [-h] [-e] [-d] [-a] [-u | -m | --extract-srt] [file ...]

positional arguments:
  file                srt file location, default all .srt files in current folder

optional arguments:
  -h, --help          show this help message and exit
  -e, --english, -en  handle only ENG subtitles
  -d, --delete        delete the original .srt file
  -a, --all-dir       process all .srt/.ass in child dir
  -u, --update-ass    update .ass to custom style
  -m, --merge-srt     merge srts
  --extract-srt       extract srt
```


### 参考项目
> https://github.com/ewwink/python-srt2ass
> https://code.google.com/archive/p/subindex/
> https://github.com/LittleAprilFool/subtitle-merger