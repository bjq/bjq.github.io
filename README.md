
Websites for you and your projects.
You get one site per GitHub account and organization, and unlimited project sites.
https://pages.github.com/

1, 创建以用户名命名的库地址（bjq.github.io）
在github网站上，用户名登录后创建库，用户名.github.io
github.com/bjq/bjq.github.io.git
git clone https://github.com/bjq/bjq.github.io

2, 提交文档到github库中
cd bjq.github.io
echo "# bjq.github.io" >> README.md
echo "Hello World" > index.html

git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/bjq/bjq.github.io.git
git push -u origin master


git add --all
git commit -m "Initial commit"
git push -u origin master


"# bjq.github.io" 
