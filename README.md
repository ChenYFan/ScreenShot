# 友链全自动截图
原项目为https://github.com/ChenYFan/ScreenShot
向<https://github.com/Akilarlxh/ScreenShot/blob/main/.github/workflows/get.yml>按照格式提交PR【禁止更改大小参数】

添加一行
```
curl https://image.thum.io/get/width/1024/crop/768/https://<YourDomain>/ -o <YourDoamin>.jpg
```
允许非友链添加截图请求

默认大小1024\*655
可在<https://cdn.jsdelivr.net/gh/ChenYFan/ScreenShot@gh-pages/>看到
**可能不适配**pjax

【本来是直接txt文件批量下载的，奈何GithubAction的curl不能识别大括号下载方式】
