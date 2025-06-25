# AI InfraSys Blog

1. 本地测试的时候 先参考[hugo配置方法](https://gohugo.io/getting-started/quick-start/),或者也有一些不错的CSDN网站也不错



## 本地测试方法

* config.yml把baseURL换成本地的

```bash
#baseURL: "https://infrasys-ai.github.io/"
baseURL: "http://localhost:1313/"
```


* content/_index.md下面的把background_image换成本地图片，注释从cdn里面得到的那个

```bash
    background_image: "/image/galaxy.jpg"
    # background_image: "https://cdn.jsdelivr.net/gh/Infrasys-AI/infrasys-ai.github.io@main/static/img/galaxy.webp"
```

* 在powershell里面运行 `hugo server --ignoreCache`