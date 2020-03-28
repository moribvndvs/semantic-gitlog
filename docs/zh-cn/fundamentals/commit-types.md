# 提交类型

## 常规类型

| 类型       | 标题                     | Emoji | 版本    | 说明                                                                                 |
|:----------:|--------------------------|:-----:|:-------:|--------------------------------------------------------------------------------------|
| `feat`     | Features                 |  ✨   | `minor` | 新增功能或模块。                                                                     |
| `refactor` | Code Refactoring         |  📦   | -       | 既无新增功能又无错误修复的更改。                                                     |
| `perf`     | Performance Improvements |  🚀   | `patch` | 做出了性能优化的更改。                                                               |
| `fix`      | Bug Fixes                |  🐛   | `patch` | Bug 修复。                                                                           |
| `chore`    | Chores                   |  ♻   | `patch` | 不涉及源代码和测试的更改。                                                           |
| `revert`   | Reverts                  |  🗑   | `patch` | 回滚到之前版本的更改。                                                               |
| `docs`     | Documentation            |  📚   | `patch` | 仅针对文档或注释的更改。                                                             |
| `style`    | Styles                   |  💎   | -       | 不影响代码含义的更改(空白字符、格式化、分号缺失等)。                                 |
| `test`     | Tests                    |  🚨   | -       | 添加或修正测试用例的更改。                                                           |
| `build`    | Builds                   |  🛠   | `patch` | 影响构建系统或外部依赖项的更改 (例如: gulp, broccoli, npm等)。                   |
| `ci`       | Continuous Integrations  |  ⚙   | -       | 针对CI配置文件和脚本的更改 (例如: travis, circle, browser-stack, sauce-labs等)。 |

## 特殊类型

| 类型             | 标题             | 版本         |
|:----------------:|------------------|:------------:|
|`BREAKING_CHANGE` | Breaking Changes | `major`      |
|`DEPRECATED`      | Deprecations     | 跟随提交类型 |
