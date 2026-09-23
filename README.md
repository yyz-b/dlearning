# dlearning
# 1、服务器链接
## 选择服务器类型
<img width="794" height="832" alt="image" src="https://github.com/user-attachments/assets/9f6323e2-731c-4218-951e-7d577cfcdec3" />
## SSH配置
配置服务器网络信息与访问配置
<img width="918" height="666" alt="image" src="https://github.com/user-attachments/assets/fd9d0f38-3a0e-491c-94a6-cab87c6014ef" />
<img width="1366" height="484" alt="image" src="https://github.com/user-attachments/assets/2f2cc72b-e808-4749-ae27-c26bb004bb84" />
在VScode中的remote-ssh插件下新建远程链接，连接到目标服务器
在终端执行后续命令
<img width="2018" height="134" alt="image" src="https://github.com/user-attachments/assets/43d4ceff-c23e-4ed2-877b-ef9145da7066" />

# 2、环境搭建
## 检查驱动
<img width="1412" height="730" alt="image" src="https://github.com/user-attachments/assets/ae0c9b6d-dd7b-4ece-abf8-030870b88239" />
## 安装 Conda
Conda 的下载：
选择从清华镜像网站下载 Conda
<img width="1736" height="460" alt="image" src="https://github.com/user-attachments/assets/d820010c-a845-4f9d-bf8e-7208f9f2dcc1" />
安装并初始化
<img width="1710" height="1068" alt="image" src="https://github.com/user-attachments/assets/8281d943-4c14-4f3e-904a-1c799f56b7e6" />
查看 Conda 版本
<img width="1272" height="72" alt="image" src="https://github.com/user-attachments/assets/7c44b4ee-a105-42d1-9475-cbf26ae36991" />
## 安装 CUDA Toolkit 
根据驱动选择对应版本的 CUDA（12.4）
<img width="2566" height="832" alt="image" src="https://github.com/user-attachments/assets/274a9685-94fc-40b8-9f9d-0a5d014a5f1e" />
执行下载语句
<img width="2944" height="568" alt="image" src="https://github.com/user-attachments/assets/b0c6e9a9-b2fb-4bc8-9970-a77aad76289f" />
下载好后安装，并配置环境变量。
注意：修改安装的默认目录，放到/mnt/workspace下，因为PAI-DSW 中明确建议持久化的是/mnt/workspace
<img width="2258" height="134" alt="image" src="https://github.com/user-attachments/assets/329372bf-1a68-4c8c-a582-1dd096e60abe" />
检查版本
<img width="884" height="210" alt="image" src="https://github.com/user-attachments/assets/1a98ea2b-13b4-489e-8014-71f7ae73fef8" />
## 安装 cuDNN 
选择与 CUDA 版本适配的 cuDNN 
<img width="2396" height="964" alt="image" src="https://github.com/user-attachments/assets/90b73243-9cce-40c6-b695-787b97631a97" />
下载后解压缩
<img width="1678" height="236" alt="image" src="https://github.com/user-attachments/assets/a004d2ff-c167-48d7-b073-bbf9084fda6f" />
将解压后的头文件和库复制到 cuda 目录中
<img width="1796" height="140" alt="image" src="https://github.com/user-attachments/assets/898f12a5-d9c9-41a7-8d47-7278cf9c70be" />
<img width="1764" height="104" alt="image" src="https://github.com/user-attachments/assets/5c5048b7-c29f-4d4e-a26e-709c038a8a3c" />
检查 cuDNN 版本
<img width="2312" height="208" alt="image" src="https://github.com/user-attachments/assets/5b885923-37ca-4a8a-bce9-87974682a0e4" />
