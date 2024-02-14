
#创建虚拟环境
mkdir project_x
cd project_x
python -m venv name_of_venv

#激活虚拟环境
source name_of_venv/bin/activate

#退出虚拟环境
deactivate



#其他
pip freeze > name_of_venv_requirements.txt    #用来列出当前所有包的版本并转存到name_of_venv_requirements.txt文件
pip install -r name_of_venv_requirements.txt  #安装name_of_venv_requirements.txt文件中列出的包   #-i https://mirrors.aliyun.com/pypi/simple/   #指定镜像


