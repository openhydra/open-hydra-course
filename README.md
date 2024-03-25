# open-hydra-course

这个项目是给所有共享 openhydra 课程的贡献项目

## 如何贡献您的课程

* 下载项目 `git clone git@github.com:openhydra/open-hydra-course.git`
* 在 `courses` 目录下创建一个新的目录，目录名为您的课程名比如 `cnn-course1` 那么您的目录结构会是这样的 `courses/cnn-course1`
* 请参照项目下 `courses/demo-course` 下的格式提交
* 如果您的课程中包含大模型文件，不建议文件超过 `50M` 当然 github 会自动屏蔽大于 `100M` 的文件，如果您有大文件您可以在课程中编写一个连接地址来提供下载，比如百度云盘或者其他可下载的位置连接即可
* 通过 `PULL REQUEST` 提交您的课程到 github 您的课程经过基本的审核后会被合并到项目中,您可以自己提交也可以请其他同事同伴帮您提交

## 课程打包周期

* 一般不出意外的情况，每周五 18:00 点我们会开始对课程进行打包，打包好的带有课程 openhydra iso 镜像会以 `ubuntu-[版本]-[日期]-live-server-amd64.iso-course.iso` 结尾来标记这个 iso 是带有课程，反之则代表改 iso 不带有课程
* 目前课程打包好的镜像目前只支持 x86_64 架构， arm 架构的镜像会在后续的版本中支持。