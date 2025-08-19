<h1 align="center">
  <br>
  <a href="https://github.com/salomonelli/best-resume-ever">
  <img src="src/assets/logo.png" alt="Markdownify" width="200"></a>
  <br>
  best-resume-ever
  <br>
</h1>

<div align="center">

[![Travis badge](https://travis-ci.org/salomonelli/best-resume-ever.svg?branch=master)](https://travis-ci.org/salomonelli/best-resume-ever)

</div>

<h4 align="center">
  用Vue和LESS快速美观地构建基于多个模板的简历
</h4>

<br>
<br>

<p align="left">
<p>Cool<br>
<img src="src/assets/preview/resume-cool.png" width="150" style="margin-right:5px; border: 1px solid #ccc;" />
<img src="src/assets/preview/resume-cool-rtl2.png" width="150" style="margin-right:5px; border: 1px solid #ccc;" />
<img src="src/assets/preview/resume-cool-rtl.png" width="150" style="margin-right:5px; border: 1px solid #ccc;" />
</p>
<p>Creative<br>
<img src="src/assets/preview/resume-creative.png" width="150" style="margin-right:5px; border: 1px solid #ccc;" />
</p>
<p>Green<br>
<img src="src/assets/preview/resume-green.png" width="150" style="margin-right:5px; border: 1px solid #ccc;" />
</p>
<p>Purple<br>
<img src="src/assets/preview/resume-purple.png" width="150" style="margin-right:5px; border: 1px solid #ccc;" />
</p>
<p>Side Bar<br>
<img src="src/assets/preview/resume-side-bar.png" width="150" style="margin-right:5px; border: 1px solid #ccc;" />
<img src="src/assets/preview/resume-side-bar-rtl.png" width="150" style="margin-right:5px; border: 1px solid #ccc;" />
<img src="src/assets/preview/resume-side-bar-projects.png" width="150" style="margin-right:5px; border: 1px solid #ccc;" />
</p>
<p>Left Right<br>
<img src="src/assets/preview/resume-left-right.png" width="150" style="margin-right:5px; border: 1px solid #ccc;" />
<img src="src/assets/preview/resume-left-right-rtl.png" width="150" style="margin-right:5px; border: 1px solid #ccc;" />
<img src="src/assets/preview/resume-left-right-projects.png" width="150" style="margin-right:5px; border: 1px solid #ccc;" />
</p>
<p>Material Dark<br>
<img src="src/assets/preview/resume-material-dark.png" width="150" style="margin-right:5px; border: 1px solid #ccc;" />
<img src="src/assets/preview/resume-material-dark-projects.png" width="150" style="margin-right:5px; border: 1px solid #ccc;" />
</p>
<p>Oblique<br>
<img src="src/assets/preview/resume-oblique.png" width="150" style="margin-right:5px; border: 1px solid #ccc;" />
<img src="src/assets/preview/resume-oblique-rtl.png" width="150" style="margin-right:5px; border: 1px solid #ccc;" />
<img src="src/assets/preview/resume-oblique-projects.png" width="150" style="margin-right:5px; border: 1px solid #ccc;" />
</p>

<br>
<br>

## 使用方法

1. 应用该模板，克隆该项目。

2. 进入项目目录 (比如. `cd best-resume-ever`)。高版本的node需要先添加环境变量NODE_OPTIONS=--openssl-legacy-provider。

3. 运行 `npm install`，等待命令完成。

4. 在`resume/`目录下面定制简历: 在`data.yml`文件中编辑建立内容。默认的简历照片是`id.jpg`。可以用自己的照片重命名成`id.jpg`，替换掉默认照片。

5. 运行`npm run dev`预览. 这个命令会启动服务并在8080端口监听。 浏览器里打开 [这个地址](http://localhost:8080/#) . 在模板列表中选择你想要的模板，就能预览到对应的简历内容了。

![Resume previews](/readme-images/resumePreviews.png)

6. 执行`npm run export`导出成pdf。
   为了避免两个`npm run`命令的冲突, 需要先停掉`npm run dev`然后再执行。
   所有的简历都会在 `pdf/` 目录下生成。

<br>

## 创建更新模板

请先阅读<a href="DEVELOPER.md">开发者文档</a>。

<br>

## 许可证

[MIT](https://github.com/salomonelli/best-resume-ever/blob/master/LICENCE.md)
