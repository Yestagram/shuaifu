# Shuaifu
Yet another language

[![License](https://img.shields.io/github/license/yestagram/shuaifu.svg?color=blue&style=flat-square)](https://github.com/yestagram/shuaifu/blob/master/LICENSE)
[![PyPI](https://img.shields.io/pypi/v/shuaifu.svg?color=3776AB&logo=pypi&logoColor=white&style=flat-square)](https://pypi.org/project/shuaifu/)
![PyPI - Downloads](https://img.shields.io/pypi/dm/shuaifu.svg?logo=python&logoColor=white&style=flat-square)
![Verify](https://img.shields.io/badge/Shuaifu-Verify-brightgreen.svg?style=flat-square)


## Install

```shell
pip install shuaifu
```

## Usage

```python
import shuaifu

shuaifu.believe() # print believe words 
print(shuaifu.get_version()) # print version
print(shuaifu.translate('woxbyhukfu!')) # translate into pinyin
```

or

```python
import shuaifu

shuaifu.xbyh() # uuiuxbyhwfbf
print(shuaifu.bjbf()) # uuiubjbf
print(shuaifu.fjyi('woxbyhukfu!')) # fjyidcpbyb
```

### Get Holidays

```python
import shuaifu

if __name__ == '__main__':
    startYear = 2000
    count = 10
    for i in shuaifu.holidays(startYear,count):
        print(i)
```

or

```python
import shuaifu

if __name__ == '__main__':
    kdui = 2000
    uull = 10
    for i in shuaifu.jxqi(kdui,uull):
        print(i)
```

the out put will be

```text
2002-12-14
2003-12-14
2008-12-14
```

### Advanced Usage

```python
import shuaifu

@shuaifu.believe
def hello(name):
    print('Hello '+ name)
    
if __name__ == '__main__':
    hello('World')
```

the output will be

```text
函数hello受到了感化,函数hello开始信仰帅副了!
函数hello沐浴教旨,努力工作,终于有了结果
Hello World
```
