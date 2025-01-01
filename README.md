# プロジェクトフォルダを作成
mkdir your-repository
cd your-repository

# 必要なファイルを作成
touch index.html coupon.html styles.css

# Git初期化
git init

# GitHubリポジトリをリモートとして追加
git remote add origin https://github.com/your-username/your-repository.git

# ファイルをステージングしてコミット
git add .
git commit -m "Initial commit"

# GitHubにプッシュ
git branch -M main
git push -u origin main
