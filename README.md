# DirDar v1.0
  
## Description
<b>🏴‍☠️ bypass forbidden directories - find and identify dir listing - you can use it as directory brute-forcer as well</b><br>

### Compatabily
This tool is compatible with all kind of operating systems as long as you have GO compiler installed

## Install

You can use this command if you have Go installed and configured.

```
go get -u github.com/m4dm0e/dirdar
```

Or you can [download a release](https://github.com/m4dm0e/dirdar/releases).
To make it easier to execute you can put the directory to the binary in your environment variable `%PATH%`.

<p align="center">
    <sub>
  </sub>
  <br>
  <!--Tweet button-->
  <a href="https://twitter.com/intent/tweet?url=https%3A%2F%2Fgithub.com%2Fm4dm0e%2Fdirdar&text=DirDar%20is%20a%20tool%20that%20searches%20for%20(403-Forbidden)%20directories%20to%20break%20it%20and%20get%20dir%20listing%20on%20it." target="_blank">Share on Twitter!
  </a>
  <br><br />
  <a href="https://twitter.com/m4dm0e"><img alt="Website" src="https://img.shields.io/twitter/follow/m4dm0e.svg?style=flat-square&logo=twitter"></a>
<a href="https://www.linkedin.com/in/Albarbari/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Mohammed%20Al%20Barbari-blue?style=flat-square&logo=linkedin"></a>
<a href="https://m4dm0e.github.io/"><img alt="Website" src="https://img.shields.io/badge/Website-m4dm0e.github.io-blue?style=flat-square&logo=google-chrome"></a>
<br />

## Tool screen:
* Linux


  <img src="statics/img/firstScreen.png" alt="linux" ></a>


* Windows

  <img src="statics/img/windows.JPG" alt="windows" ></a>
  
  
## Help&Flags

```
  -threads int
    	Number of threads (Defaulf 40)
  -err
    	If you want to show errors!(Includes 404 errors) [True-False]
  -only-ok
    	Print out only OK (Bypassed and dir listing) 
  -single string
    	Only scan single target e.g (-single https://example.com/)
  -t int
    	Set the timeout of the requests (default 10000)
  -wl string
    	Forbidden directories WordList

```

* Screenshot

  <img src="statics/img/help.png" alt="help" ></a>

## Bugs found by DirDar: (Will share the write up ASAP)
* BackUp files at [MTN Group](https://hackerone.com/mtn_group?type=team) (Triaged)
* OLD php scripts to SQLi at [MTN Group](https://hackerone.com/mtn_group?type=team) (Triaged)
* OLD Files to information disclosure at [BOSCH](http://psirt.bosch.com/) (Triaged)


## Review:

[![asciicast](https://asciinema.org/a/391851.svg)](https://asciinema.org/a/391851)


