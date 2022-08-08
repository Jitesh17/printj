# printj

[![Python 3.6](https://img.shields.io/badge/python-3.6-blue.svg)](https://www.python.org/downloads/release/python-360/)
![Build Status](https://github.com/jitesh17/printj/actions/workflows/python-publish.yml/badge.svg)
[![license: MIT](https://img.shields.io/badge/license-MIT-orange.svg)](https://opensource.org/licenses/MIT)



Print log info and color text, speak text and helps debugging.



## Installation
### Method 1: Pip install

```python
pip install printj
```

### Method 2: Git clone

```python
git clone https://github.com/jitesh17/printj.git
cd printj
pip install -e .
```


## Usage

- Script
    ```python
    import printj

    printj.red('YOUR TEXT')
    printj.bold('YOUR TEXT')
    printj.blue.italic_on_yellow('YOUR TEXT')
    printj.say('YOUR TEXT')  # It will convert text to speech
    ```
- Output
    
    ![](https://i.imgur.com/zaRgPU3.png)

 
