# 【赤石】（伪）在arch系linux中使用apt指令

#### 注意！
请确保您使用的系统是基于arch的Linux发行版，而不是一辆发霉的汽车

### 使用方法
1. 打开您高贵华丽时尚帅气简约透明云母亚克力仙女下凡阳光彩虹重金属... (编不下去了)的终端
2. 手指在键盘上如蝴蝶般翩然起舞，敲下`cd /usr/local/bin/`，回车
3. 接着输入`git clone https://github.com/Oiiai/apt-in-archlinux.git`，回车
4. 等待指令结束
5. 进入工作目录下的`apt-in-archlinux/`文件夹（这是不小心执行第3步的后果）
6. 找到`apt`文件，并把它剪贴（或者复制）到上级目录（也就是`/usr/local/bin/`）
7. 聪明的你会发现，此时在终端输入`apt update`、`apt install 包名`等指令居然能够正常输出，而不是可恶的
   ```bash
   sudo: apt：找不到命令
   ```
9.  **（最重要的一步！！）** 把`apt-in-archlinux/`文件夹和您刚刚粘贴的`apt`文件一起删除！
10.  恭喜您，成功地浪费了人生中宝贵的1分钟
