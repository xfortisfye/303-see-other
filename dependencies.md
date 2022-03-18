# Guide: Dependencies

## Description
Guide to installing dependencies

-----
## Environment Path

1. Open Environment Variables
    1. Shortcut: Using Run
        1. <kbd>⊞ Win</kbd> + <kbd>R</kbd>
        2. Enter `rundll32.exe sysdm.cpl,EditEnvironmentVariables`
    2. Manual: 
        1. Right-click on 'This PC' > Properties > Advance System Settings > Environment Variables
2. Under System Variable, Select PATH
3. Click on Edit, enter location
4. Key in the specified value.

-----
## Java
#### Windows
1. Download [installer](https://www.oracle.com/java/technologies/downloads)
2. Set up [environment path](https://github.com/xfortisfye/303-see-other/blob/main/dependencies.md#environment-path)
    1. Usually value is `C:\Program Files\Java\jdk-13.0.2\bin`

-----
## Make
1. [Install](https://sourceforge.net/projects/gnuwin32/files/make/3.81/make-3.81.exe/download?use_mirror=nchc&download=) Make
2. Set up [environment path](https://github.com/xfortisfye/303-see-other/blob/main/dependencies.md#environment-path). 
   1. Usually value is `C:\Program Files (x86)\GnuWin32\bin`

### Run the program
```bash
> cd C:\Path\to\root_folder
> make
```

-----
## Python

#### Windows
1. Download [manually](https://www.python.org/downloads/) or direct download of the following version:
    1. [Python 3.9.10 64-bit](https://www.python.org/ftp/python/3.9.10/python-3.9.10-amd64.exe)
    2. [Python 3.8.5 64-bit](https://www.python.org/ftp/python/3.8.5/python-3.8.5-amd64.exe)
    3. [Python 2.7.18 64-bit (last update of Python 2)](https://www.python.org/ftp/python/2.7.18/python-2.7.18.amd64.msi)
2. Set up [environment path](https://github.com/xfortisfye/303-see-other/blob/main/dependencies.md#environment-path)
    1. Usually value is `C:\Python38\`

-----
### pip
1. `curl https://bootstrap.pypa.io/get-pip.py > get-pip.py`
2. `python get-pip.py`
3. Update pip with `python -m pip install --upgrade pip`

Guidelines: https://pip.pypa.io/en/stable/installation/

### Python packages
1. Install Python Packages
```bash
> cd \Path\to\root_folder
> pip install -r requirements.txt
```
2. Save Python Packages into `requirements.txt`
```bash
> pip freeze > requirements.txt
```

-----



