
mac 系统

brew install python
pip install --upgrade pip
pip install virtualenv
brew install python3

测试
python -V
python3 -V
pip install xx
pip3 install xx

写 /Users/E02/C/Program_Files/bash_profile/python.sh
```bash
#
# python2 pip
#
export PIP_REQUIRE_VIRTUALENV=true
#

```

+
测试
cd tmp
mkdir app
cd tmp/app
virtualenv --no-site-packages venv
cd venv && echo "*" >> .gitignore && cd ..
进入环境 cd tmp/app
source ./venv/bin/activate
退出环境
deactivate
安装依赖
pip install flask

python hello.py
