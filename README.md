## 1.创建python虚拟环境之前把虚拟环境名myenv加入到.gitignore文件中去



## 2.在本地仓库中创建一个python虚拟环境一个虚拟myenv：进入本地仓库输入命令：

```shell
# myenv是一个python虚拟环境，包含一个python解释器，pip以及其他的python package

virtualenv myenv
```



## 3.git-bash终端下，在本地仓库中激活python虚拟环境myenv(和linux中一样地操作):

```shell
 source ./myenv/Scripts/activate
```



## 4.git-bash终端下，在本地仓库中退出python虚拟环境(和linux中一样地操作): 

```shell
deactivate
```





## 5.git-bash终端下，激活虚拟环境之后便可以按照requirements.txt安装python地包:

```shell
pip install -r requirements.txt
```



## 6.git-bash终端下，运行calculator.py：

## 激活虚拟环境并且安装了必须的python package之后：python calculator.py即可使用这个计算器

```shell
# 已经激活myenv,并且安装好了requirements.txt中的包之后，便可以成功运行calculator.py

python calculator.py
```

