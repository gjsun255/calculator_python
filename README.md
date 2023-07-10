## 1.创建python虚拟环境之前把虚拟环境名myenv加入到.gitignore文件中去

## 2.在本地仓库中创建一个python虚拟环境myenv：进入本地仓库输入命令：virtualenv myenv

## 3.myenv是一个python虚拟环境：包含一个python解释器和多个python package

## 4.git-bash终端下，在本地仓库中激活python虚拟环境(和linux中一样地操作): source ./myenv/Scripts/activate

## 5.git-bash终端下，在本地仓库中退出python虚拟环境(和linux中一样地操作): deactivate

## 6.git-bash终端下，激活虚拟环境之后便可以按照requirements.txt安装python地包：pip install -r requirements.txt

## 7.git-bash终端下，运行calculator：激活虚拟环境并且安装了必须的python package之后：python calculator.py即可使用这个计算器
