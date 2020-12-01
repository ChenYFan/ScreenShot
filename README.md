# 友链全自动截图
原项目为<https://github.com/ChenYFan/ScreenShot>

向<https://github.com/Akilarlxh/ScreenShot/blob/main/.github/workflows/get.yml>按照格式提交PR【禁止更改大小参数】

添加一行
```
curl https://image.thum.io/get/width/400/crop/800/allowJPG/wait/20/noanimate/https://<YourDomain>/ -o <YourDoamin>.jpg
```
允许非友链添加截图请求

默认大小400\*266  默认宽度未width后面的像素值。crop的计算方法有些不同，虽然官方文档说是高度像素，但是实际测试发现应该是height=width*(crop/1200)。具体文档可以访问https://image.thum.io查看。

可在<https://cdn.jsdelivr.net/gh/Akilarlxh/ScreenShot@gh-pages/>看到预览图

**可能不适配**pjax

【本来是直接txt文件批量下载的，奈何GithubAction的curl不能识别大括号下载方式】
