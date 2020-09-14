### List

```shell
conda list 查看安装了那些包
conda env list 查看当前存在哪些虚拟环境
conda update conda 检查更新当前conda
```

### 创建虚拟环境

```shell
conda create -n your_env_name python=x.x
```

### 激活或切换不同python版本

```shell
python --version 检查当前python的版本

激活虚拟环境
Linux : source activate your_env_name
Windows : activate your_env_name
```

### 安装额外的包

```shell
conda install -n your_env_name [package]

```

### 移除环境

```shell
conda remove -n your_env_name --all
```

### 关闭环境

```shell
Linux: source deactivate
Windows: deactivate
```

### 配置清华源

```shell
conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/free/
conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/main/
conda config --set show_channel_urls yes
```

### Jupyter Notebook切换conda环境

```shel	
1.激活你要用的环境
conda activate <环境名称>
2.安装ipykernel
conda install ipykernel
3.conda环境注入
python -m ipykernel install --user --name your_env --display-name "your_display"
your_env 是你的conda环境名称
your_display：将是你在notebook中看到的名称。
```

