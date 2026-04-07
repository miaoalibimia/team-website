# 团队网站协作教程

## 准备工作：安装 GitHub Desktop

1. 去 https://desktop.github.com 下载并安装 **GitHub Desktop**
2. 2. 打开后用你的 GitHub 账号登录
  
   3. ---
  
   4. ## 第一步：克隆仓库到本地（只需做一次）
  
   5. 1. 打开 GitHub Desktop，点击左上角 **File → Clone Repository**
      2. 2. 切换到 **URL** 标签，输入：`https://github.com/miaoalibimia/team-website`
         3. 3. 选择你想存放项目的文件夹，点击 **Clone**
            4. 4. 等待下载完成，项目就出现在你电脑上了
              
               5. ---
              
               6. ## 第二步：每次开始工作前，先同步最新版本
              
               7. > 这一步非常重要，每次开始改代码之前都要做！
                  >
                  > 1. 打开 GitHub Desktop，左上角确认当前是 **main** 分支
                  > 2. 2. 点击顶部的 **Fetch origin**，再点 **Pull origin**（如果出现的话）
                  >    3. 3. 这样你就拿到了大家最新的修改
                  >      
                  >       4. ---
                  >      
                  >       5. ## 第三步：创建自己的分支
                  >      
                  >       6. > 不要直接在 main 上改！在自己的分支上工作，互不干扰。
                  >
                  > 1. 点击顶部中间的 **Current Branch** 按钮
                  > 2. 2. 点击 **New Branch**
                  >    3. 3. 输入分支名，格式建议是：`你的名字-功能`，比如 `alice-navbar` 或 `bob-homepage`
                  >       4. 4. 点击 **Create Branch**
                  >         
                  >          5. ---
                  >         
                  >          6. ## 第四步：修改代码并提交
                  >         
                  >          7. 1. 打开你本地的项目文件夹（GitHub Desktop 左下角可以点 **Show in Finder** 找到位置）
                  > 2. 用你习惯的编辑器（VS Code 等）修改代码
                  > 3. 3. 改完之后回到 GitHub Desktop，左边会显示你改动的文件列表
                  >    4. 4. 在左下角的 **Summary** 框里写一句简短的说明，比如：`完成了首页的导航栏`
                  >       5. 5. 点击蓝色的 **Commit to [你的分支名]** 按钮
                  >          6. 6. 点击右上角的 **Push origin**，把改动上传到 GitHub
                  >            
                  >             7. ---
                  >            
                  >             8. ## 第五步：发起 Pull Request，申请合并到主版本
                  >            
                  >             9. 1. Push 完之后，GitHub Desktop 会提示 **Create Pull Request**，点击它（会跳转到网页）
                  >                2. 2. 写一下你做了什么改动，点击 **Create Pull Request**
                  > 3. 通知其他组员来看一下，确认没问题后由仓库管理员点击 **Merge** 合并到 main
                  >
                  > 4. ---
                  >
                  > 5. ## 如果想回到之前的版本
                  >
                  > 6. 在 GitHub 网页上，进入仓库 → 点击 **Commits**，可以看到所有历史版本，每一条都有对应的人和时间，随时可以回滚。
                  >
                  > 7. ---
                  >
                 
