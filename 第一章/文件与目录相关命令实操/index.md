### 学习环境
本次课程使用的是linux ubuntu学习环境，
在这个学习环境下你可以学习到有关linux相关的常用命令的使用，
让你具备一定的linux操作能力和运维能力

#### 打开shell
- 在实验工具中打开shell工具

#### 查看目录文件
执行ls命令
```bash
ls
```{{exec}}

# 下一步
#### 查看更多目录文件
执行ls -a命令
```bash
ls -a
```{{exec}}

# 下一步
#### 查看所在目录
执行pwd命令
```bash
pwd
```{{exec}}

# 下一步
#### 创建test目录
执行mkdir test命令
```bash
mkdir test
```{{exec}}

# 下一步
#### 创建file.txt文件
执行touch test/file.txt命令
```bash
touch test/file.txt
```{{exec}}

# 下一步
#### 向file.txt文件写入hello
执行echo "hello" > test/file.txt命令
```bash
echo "hello" > test/file.txt
```{{exec}}

# 下一步
#### 查看file.txt文件内容
执行cat test/file.txt命令
```bash
cat test/file.txt
```{{exec}}

# 下一步
#### 拷贝test目录
执行cp -r test temp命令
```bash
cp -r test temp
```{{exec}}

# 下一步
#### 删除test目录
执行rm -rf test命令
```bash
rm -rf test
```{{exec}}

# 下一步
#### 重命名temp目录
执行mv temp test_temp命令
```bash
mv temp test_temp
```{{exec}}
