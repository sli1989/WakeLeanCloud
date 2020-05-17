# WakeLeanCloud

自动唤醒你的LeanCloud，Forked from [Dreamy.TZK](https://cloud.tencent.com/developer/article/1628950)

1. 选择`setting`，点击`Developer settings`。
1. 选择`Personal access tokens`，添加一个新的TOKEN，设置名字为`GITHUB_TOKEN` , 然后勾选 `repo` , `admin:repo_hook` , `workflow` 等选项，最后点击Generate token即可。
1. 成功FORK后，进入项目的`setting`。选择`Secrets`，添加Name为`SITE`，Value为`你的leancloud的后台地址`（也就是评论管理的后台地址）。其中Value可以是多个地址，用英文逗号分隔，不要中中文逗号。
1. 接下来对自己的项目点个star就能启动了，启动后请切换到actions，看看是否运行成功。默认是每天8:00-24:00时每20分钟运行一次。(GitHub时间稍有延迟，大概时2-5分钟。)
