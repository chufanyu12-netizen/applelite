# HTTPS 方式（推荐新手）
git remote add origin https://github.com/your-username/applelite.git

# SSH 方式（需配置 SSH key）
# git remote add origin git@github.com:your-username/applelite.git# 重命名主分支为 main（GitHub 默认）
git branch -M main

# 首次推送并设置上游
git push -u origin main
