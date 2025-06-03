# HDU-Letter-Template

- **Language**: [English](README.md), 简体中文

![Author](https://img.shields.io/badge/Author-Huangwei_Chen-red)
![Last Commit](https://img.shields.io/github/last-commit/HovChen/HDU-Letter-Template?color=yellow)
![Repo Size](https://img.shields.io/github/repo-size/HovChen/HDU-Letter-Template)
![Language](https://img.shields.io/badge/language-latex-orange)
![License](https://img.shields.io/github/license/HovChen/HDU-Letter-Template?color=green)

本项目为杭电信件模板，基于LaTeX实现，适用于各类正式信件等文档的排版。

## 项目结构

- `main.tex`：主LaTeX文件，编译入口。
- `letterContent.tex`：信件正文内容，可根据实际需求修改。
- `pic/`：图片资源文件夹，包括校徽、签名等图片。
    - `HDU_Logo.png`：杭电校徽
    - `HDU_Logo_bg.png`：带背景的校徽
    - `TOBEsigned.png`：待签名图片
    - `signature.png`：签名图片

## 使用方法

### 本地编译

1. 安装LaTeX发行版（推荐TeX Live或MiKTeX）。
2. 克隆或下载本项目到本地。
3. 根据实际需求，编辑`letterContent.tex`文件，填写信件内容。
4. 在项目根目录下，使用如下命令编译：

   ```bash
   xelatex main.tex
   ```

5. 编译成功后，将生成`main.pdf`，即排版好的信件。

### 在线编译（Overleaf）

1. 访问 [Overleaf](https://www.overleaf.com/) 并注册账号。
2. 新建项目后，将本项目中的所有文件（包括`main.tex`、`letterContent.tex`及`pic/`文件夹下的图片）上传至Overleaf项目根目录。
3. 编辑`letterContent.tex`填写信件内容。
4. 点击“重新编译”即可在线生成PDF，无需本地安装任何软件。

## 注意事项

- 如需更换图片，可将新图片替换`pic/`目录下对应文件。
- 若需调整版式或样式，可修改`main.tex`中的相关设置。

## 许可证

本项目仅供学习与交流使用，禁止用于商业用途。

## 参考

本项目参考并致敬 [ByteDance-Letter-Template](https://github.com/leungll/ByteDance-Letter-Template)。