# Any Question
[![Gitter](https://badges.gitter.im/taipeipy/taipeipyweb.svg)](https://gitter.im/taipeipy/taipeipyweb?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

# Installation
## Download desktop application
The download link is at the top right corner in
[Lektor]( https://www.getlektor.com/).

## Command Line Interface Only
Reference [Lektor CLI](  https://www.getlektor.com/docs/installation/  ). For different OS, you need choose corresponding installation instructions.


### Precondition:
* Python 2.7 is ready. (not Python 3.x)
* ImageMagick 
  * `brew install imagemagick` for Linux/Mac OS.
  * `choco install imagemagick` for Windows Users.
    * Install [choco](https://chocolatey.org/).
  * Make sure the global `PATH` variable is set up. 

### For Linux/Mac OS users
```bash
(sudo) curl -sf https://www.getlektor.com/install.sh | sh
```

### For Windows users
```batch
C:\> @powershell -NoProfile -ExecutionPolicy Bypass -Command "iex ((new-object net.webclient).DownloadString('https://getlektor.com/install.ps1'))" && SET PATH=%PATH%;%LocalAppData%\lektor-cli
```

### pip install
```bash
virtualenv venv
. venv/bin/activate
pip install Lektor
```

## Common Q&A
* For Mac OS, what to do if `clang` complains about `unknown argument` ?

1. Reference [here](http://goo.gl/zDxei7).

[Lektor] https://www.getlektor.com/
