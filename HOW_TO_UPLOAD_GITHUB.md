# Mac 小白上传 GitHub 步骤

下面用最简单的网页上传方式，不需要会命令行。

## 1. 确认要上传哪个文件夹

只上传这个文件夹里的内容：

```text
public-template
```

不要上传上一层的真实项目文件夹，因为那里有真实名单和课程表。

## 2. 注册或登录 GitHub

打开：

```text
https://github.com
```

如果没有账号，先注册一个。

## 3. 新建仓库

登录后：

1. 点击右上角 `+`
2. 点击 `New repository`
3. Repository name 填一个名字，比如：

```text
qun-signin-template
```

4. 如果只是自己保存，选 `Private`。
5. 如果想公开给别人看，选 `Public`。
6. 不要勾选 “Add a README file”，因为我们本地已经有 README。
7. 点击 `Create repository`。

## 4. 网页上传文件

创建仓库后，GitHub 页面上会看到：

```text
uploading an existing file
```

点击它。

然后打开 Mac 上的这个文件夹：

```text
/Users/hh/Documents/Codex/2026-05-21/qq/autox-checkin/public-template
```

把里面的文件拖进 GitHub 网页上传区域。

要上传这些文件：

```text
README.md
HOW_TO_UPLOAD_GITHUB.md
students.example.txt
courses.example.csv
config.example.json
ai_config.example.json
.gitignore
```

## 5. 提交上传

网页下面会有提交区域。

Commit message 可以写：

```text
Initial public template
```

然后点击：

```text
Commit changes
```

## 6. 上传前检查

公开仓库上传前，确认没有这些东西：

```text
真实学生名单
真实课程地点
真实 QQ 群名
API Key
手机截图
运行日志
ai_config.json
students.txt
courses.csv
config.json
```

如果不确定，就先建 `Private` 私有仓库。

## 7. 最稳建议

你现在是新手，建议先选：

```text
Private
```

等你以后熟悉 GitHub，再决定要不要公开。
