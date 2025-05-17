---
permalink: /
title: "上海地下偶像信息收集"
author_profile: false
redirect_from: 
  - /about/
  - /about.html
---

## 关于为什么要做这个东西

我做这个玩意只是觉得微博不太好用, 部分团又没有很好的时间线整理, 所以想做这样一个东西, 让大家能方便的看活.

因为个人时间有限, 所以只会更新上海的活, 不能保证比板子快, 甚至会漏掉一些活, 只能尽量在我有兴趣的时候保持.

我也是纯纯菜鸡, 没做过网页, 如你所见, 这是用学术个人主页模板用jekyll构建的网页, 托管在github上, 
所以如果你有兴趣可以发pull request或者issue一起维护
## Update logs

## GitHub Commit Timeline

以下是此仓库的 GitHub 提交时间线，展示了最近的更新记录：

{% capture git_log %}
{% shell_output %}
git log --pretty=format:"%h - %an, %ar : %s"
{% endshell_output %}
{% endcapture %}

```plaintext
{{ git_log }}
```

此时间线会在页面构建时自动更新，展示最新的提交记录。