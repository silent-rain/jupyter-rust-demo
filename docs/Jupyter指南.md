# Jupyter 指南

## 环境搭建

### 安装

```shell
pip install jupyterlab
```

### 安装扩展

```shell
# 渲染Plotly可视化图表
jupyter labextension install jupyterlab-plotly

# 主题换肤
jupyter labextension install @shahinrostami/theme-purple-please
```

### 安装 EvCxR Jupyter 内核

- [EvCxR 官网](https://github.com/google/evcxr/blob/main/evcxr_jupyter/README.md)
接下来我们来安装EvCxR Jupyter内核。EvCxR可以让Rust运行在Jupyter Notebook上。

```shell
cargo install evcxr_jupyter
evcxr_jupyter --install
```

### 查看安装的内核

```shell
jupyter kernelspec list
```

### 运行

```shell
jupyter lab
```

## Rust 使用指南

- [evcxr_jupyter_tour 示例文档](https://colab.research.google.com/github/evcxr/evcxr/blob/main/evcxr_jupyter/samples/evcxr_jupyter_tour.ipynb#scrollTo=1bMi7rv9fx3d)
- [selenium 客户端](https://www.selenium.dev/)
- [chromedriver 官网地址](https://developer.chrome.com/docs/chromedriver/downloads/version-selection?hl=zh-cn)
- [浏览器对应版本的linux chromedriver](https://storage.googleapis.com/chrome-for-testing-public/131.0.6778.87/linux64/chromedriver-linux64.zip)
