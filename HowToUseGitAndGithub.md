1.下载Git  
2.上传文件
|序号|操作|
|:--:|----|
|1   |运行 `git-bash`|
|2   |跳转到对应文件夹|
|3   |执行 `git config --global user.email "you@example.com"`，在 `you@example.com` 处输入邮箱|
|4   |执行 `git config --global user.name "Your Name"`，在 `Your Name` 处输入 Github 用户名|
|5   |执行 `git add .`|
|6   |执行 `git commit -m "SaySomething..."`，在 `SaySomething...` 处输入描述|
|7   |执行 `git remote add origin https`，在 `https` 处输入仓库网址|
|8   |执行 `git push origin`|
|9   |若Git弹出<br>`fatal: The current branch master has no upstream branch.`<br>`To push the current branch and set the remote as upstream, use`<br><br>`    git push --set-upstream origin master`<br><br>`To have this happen automatically for branches without a tracking`<br>`upstream, see 'push.autoSetupRemote' in 'git help config'.`<br>执行 `git push --set-upstream origin master`<br>再执行 `git push origin`<br>否则忽略这一步|  

3.下载文件
|序号|操作|
|:--:|----|
|1   |运行 `git-bash`|
|2   |跳转到目标文件夹|
|3   |执行 `git clone html`，在 `html` 处输入仓库网址|  

$$
\begin{aligned}
{(\frac{a}{b})}^{\frac{c}{d}} \\ &=
\sqrt[d]{(\frac{a}{b})^c} \\ &=
\sqrt[d]{\frac{a^c}{b^c}} \\ &=
\frac{\sqrt[d]{a^c}}{\sqrt[d]{b^c}}(a,b,c,d\in\mathbf N)
\end{aligned}
$$
