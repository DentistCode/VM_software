[toc]

# VM_software
（自用）虚拟机软件下载
练手的东西，用于学习html及虚拟机相关内容，有空就完善

[toc]

### Roadmap
1. 制作html网页版+手动下载到文件夹里手动更新软件
2. 制作html网页版（同步最新版本）+自动下载到文件夹里自动更新
3. 制作脚本（可能是shell、可能是html）。扔虚拟机里，勾选后自动下载
4. 除了软件下载外，windows安装一键配置（e.g.任务栏、edge设置、桌面图标等。。。）


### Todo
* 主线
  - [ ] 整理完整的流程体系
  - [ ] 跟着roadmap学习完流程
* 同步进行：
  - [ ] 学习edge的隐私防护学习/对比火绒
  - [ ] 虚拟机的安全性学习
  - [ ] 开源软件的风险性（目前知道0day）
### 一些构想
* edge的一键设置可以尝试用网页的方式访问，比如`edge://settings/privacy`，`edge://flags/#enable-parallel-downloading`
* 可以整一个六边形。通用虚拟机属性是六边形图的均衡一些，专用虚拟机按照其发展方向进行发展
---

## 综述
优先用开源软件
### 通用软件

- everything
- Geekuninstaller卸载器
- Tampermonkey

### 激活软件

- KMS https://github.com/zbezj/HEU_KMS_Activator

### code相关

- vscode
- clash
- miniconda/anaconda

### 压缩软件

- 7zip（开源）
- BandiZip
- WinRAR

### 下载

- 夸克、idm、迅雷、百度云、阿里云
- greasyfork的资源嗅探和修改

### 杀毒

- 360杀毒

## Windows常用设置
- 最先的下载工作
  - windows系统更新
  - edge自身更新 
- 防止windows追踪
    - ****optimizer-开源Windows优化器****
        - https://github.com/hellzerg/optimizer
    - WPD（停更 1.5.2042 RC 1 10-17-2021）
        - [WPD | Privacy dashboard for Windows](https://wpd.app/)
- 设备管理器禁用蓝牙、麦克风
- 激活
- windows自身习惯
  - 右键个性化—>桌面显示计算机
    - ![image](https://github.com/FushengTao/VM_software/assets/86056063/b4008a36-e7c3-4af0-ac3c-9f3fe9e51061)
  - 任务栏搜索调小
  - 文件夹打开隐藏和拓展名
    - ![image](https://github.com/FushengTao/VM_software/assets/86056063/db86b8b8-1e34-4190-8bf7-696809b70d8f)
  - 文件夹选项
    -  ![image](https://github.com/FushengTao/VM_software/assets/86056063/419e74e7-eb08-49ab-882f-691f752e28d8)
- edge使用习惯（有待学习）
  - edge多线程
    `edge://flags/#enable-parallel-downloading`
  - 侧栏全关
    - ![image](https://github.com/FushengTao/VM_software/assets/86056063/1ffa3428-44a0-4b3f-bd59-fdf7e2752ec2)
  - Microsoft reward关闭
    - ![image](https://github.com/FushengTao/VM_software/assets/86056063/10cf68fa-9c0d-4e91-b2ef-734dbcbb1ded)
  - 下载切换到桌面
  - 隐私这一整页的内容
    - ![image](https://github.com/FushengTao/VM_software/assets/86056063/9160e881-b977-405b-9a65-9fdfce2f2b0c)
  - 菜单栏
    - ![image](https://github.com/FushengTao/VM_software/assets/86056063/58596151-9fea-464e-931e-f55d637d97a3)
  - 关闭拓展关闭edge后继续运行
    - ![image](https://github.com/FushengTao/VM_software/assets/86056063/40ace07e-926d-4272-b10b-0f94c4a8850d)
  - （考虑关闭）快速启动

## 类型

01下载机
  配置可以低、多下载软件
02软件试验田
  配置高、和真实环境一样
03专用防毒
  高隔离性
04隔离用
  防止追踪，比如sb的qq扫盘


