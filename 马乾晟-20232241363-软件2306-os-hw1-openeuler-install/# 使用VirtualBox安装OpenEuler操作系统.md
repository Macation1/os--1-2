# 使用VirtualBox安装OpenEuler操作系统

## 1.在OpenEuler官网下载VirtualBox

在 VirtualBox 官网下载安装程序
![](https://www.openeuler.org/assets/e02.C9OPn4uC.png)
## 2.创建虚拟机

选择 【控制】-->【新建】，填写虚拟机的配置信息，示例如下

名称：openEuler，类型：Linux，由于没有 openEuler，所以版本选择 Other Linux(64-bit)，下一步


安装的时候可以自定义安装路径如
![](https://www.openeuler.org/assets/e05.rX4_Uium.png)
设置虚拟机的内存，此内存即为虚拟机所占用的系统内存，这里将虚拟内存设置为 4G
![](https://www.openeuler.org/assets/4G.Cp5iCjwq.png)
选择【现在创建虚拟硬盘(c)】
![](https://www.openeuler.org/assets/hard.CJJWnPdQ.png)
虚拟硬盘文件类型，选择默认的【VDI（VirtualBox 磁盘映像）】，下一步
![](https://www.openeuler.org/assets/e07.XGx7EL45.png)
选择【动态分配】，下一步

分配给虚拟机的内存空间较大，使用时逐渐占用磁盘空间，闲置时自动缩减比较合理
![](https://www.openeuler.org/assets/e08.B0-xpaJy.png)
这里选择设置虚拟机硬盘大小为 64G
![](https://www.openeuler.org/assets/64G.-gTrCFxo.png)
虚拟机创建完成，openEuler 所需的硬件资源准备完毕

![](https://www.openeuler.org/assets/e10.ByfH9DNN.png)

## 3. 安装 openEuler 
启动上一步创建好的虚拟机
![](https://www.openeuler.org/assets/e11.zAEV86XH.png)
点击右侧“文件夹图标”
![](https://www.openeuler.org/assets/e12.CtZxlrGB.png)
点击注册，选择准备阶段下载好的 openEuler-20.03-LTS-x86_64-dvd.iso
![](https://www.openeuler.org/assets/e13.CAMVJ-dF.png)
选择【启动】，进入到安装界面
![](https://www.openeuler.org/assets/e14.C9nTxkZn.png)
选择 【Install openEuler 20.03-LTS】回车，进行安装
![](https://www.openeuler.org/assets/e15.DOFsWxNf.png)
选择 Continue
![](https://www.openeuler.org/assets/e16.DLAkTr3l.png)
选择要安装的磁盘，Done
![](https://www.openeuler.org/assets/e18.CORYxIcA.png)
选择 Begin Installation
![](https://www.openeuler.org/assets/e19.DeT2kA2W.png)
安装状态如下
![](https://www.openeuler.org/assets/e20.DQHcULKW.png)
选择 Root Password 设置 root 用户的密码
![](https://www.openeuler.org/assets/e21.DWWC_mH6.png)
安装完成后，选择 Reboot 重启虚拟机
![](https://www.openeuler.org/assets/e22.BVGP3ZG6.png)
显示重新回到了安装界面
![](https://www.openeuler.org/assets/e23.C9N3ER2B.png)
关闭虚拟机，选择【设置】选中 openEuler-20.03-LTS-x86_64-dvd.iso，鼠标右键，删除盘片，保存退出
![](https://www.openeuler.org/assets/e24.BP2efK2r.png)
重新启动虚拟机，显示如下界面，直接回车
![](https://www.openeuler.org/assets/e25.C1G75q6j.png)
输入用户（root）密码（安装阶段设置的密码），进入 openEuler 虚拟机
![](https://www.openeuler.org/assets/e26.BVicgI2O.png)
到这里 openEuler 虚拟机已经安装完成了