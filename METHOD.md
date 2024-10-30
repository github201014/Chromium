# Chromium 公共镜像使用方法
1. 将镜像文件完全解压至自己的硬盘上；
2. 将文件夹 chromium.git 重命名为 .git 并放在 chromium 文件夹中；
3. 将 .git 中的 config 文件替换为此仓库的 [config](https://github.com/github201014/Chromium/blob/main/config) 文件；
4. 运行以下代码以更新仓库为最新版本：

   ```bash
   cd chromium
   git fetch
   git merge
   ```
   或：
   
   ```bash
   cd chromium
   git pull
   ```
6. 将代码切换为最新状态：

   ```bash
   git checkout master
   ```
   或切换至指定 tag:
   
   ```bash
   git tag
   git checkout tag-name
   ```
