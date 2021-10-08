(start:how)=
# 如何启动项目

## 云端配置

只需要专注于编写代码即可。

## 本地配置

配置工作要在项目根目录。

首先，安装 CSS 主题：

```sh
git clone https://github.com/xinetzone/xin-css.git ./_static/xin-css
git clone https://github.com/xinetzone/w3css.git ./_static/w3css
```

其次，安装 Python 包：

```sh
conda create -n ai python=3.9
conda activate ai
pip install -r requirements.txt
conda install -c conda-forge myst-parser
conda install ipykernel
python -m ipykernel install --user --name ai --display-name "ai"
```

最后，构建书库：

```sh
jupyter-book clean .
jupyter-book build .
```

## 自定义

需要修改 `README.md`、`_config.yml`、`_toc.yml` 以匹配你的项目。