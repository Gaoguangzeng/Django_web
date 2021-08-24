虚拟环境for EFS

pip install virtualenv

cd your_workplace

virtualenv python4efs

D:\EFS_AutomServer\python4efs>cd Scripts

D:\EFS_AutomServer\python4efs\Scripts>activate

(python4efs) D:\EFS_AutomServer\python4efs\Scripts>

虚拟环境管理工具（待定、待续）

Virtaulenvwrapper，安装在系统中非虚拟环境中；

pip install virtualenvwrapper-win

创建：mkvirtualenv --python=python3 venv

安装Django

(python4efs) D:\EFS_AutomServer\python4efs>pip install django

>>> import Django

Traceback (most recent call last):

File "<stdin>", line 1, in <module>

ModuleNotFoundError: No module named 'Django'

>>> import django

>>> django.get_version()

'3.2.6'

>>>