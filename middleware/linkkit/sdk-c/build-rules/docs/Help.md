常用命令
---

| 命令                  | 解释                                                                              |
|-----------------------|-----------------------------------------------------------------------------------|
| `make distclean`      | **清除一切编译过程产生的中间文件, 使当前目录仿佛和刚刚clone下来一样**             |
| `make [all]`          | **使用默认的平台配置文件开始编译**                                                |
| `make reconfig`       | **弹出多平台选择菜单, 用户可按数字键选择, 然后根据相应的硬件平台配置开始编译**    |
| `make config`         | **显示当前被选择的平台配置文件**                                                  |
| `make help`           | **打印帮助文本**                                                                  |
| `make env`            | **打印当前编译的选项和它们的值**                                                  |
| `make <directory>`    | **单独编译被 <directory> 指定的目录, 或者叫编译单元**                             |

高级命令
---

| 命令                  | 解释                                                                              |
|-----------------------|-----------------------------------------------------------------------------------|
| `make repo-list`      | 列出当前可以更新的组件列表, 所谓组件是跨项目的功能模块, 有独立的`git`仓库         |
| `make repo-update`    | 根据输入更新所有组件或单个被选择的组件, 从线上获取其最新的`git`仓库               |
| `make test`           | 如果当前项目有编写单元测试主程序和单元测试例, 则执行UT, 统计通过率和覆盖率        |

o 访问 https://code.aliyun.com/edward.yangx/public-docs/wikis/home 可获得编译系统线上最新和最全的帮助文档
