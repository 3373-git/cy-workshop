# cy-workshop

CY工坊（CreoToolkitAddin，Creo Parametric 插件）的**发行包仓库**。

这里只放安装包和更新清单，源码不在这个仓库里。

| 文件 | 用途 |
|---|---|
| `latest.json` | 更新清单：版本号、包地址、sha256、更新说明 |
| `CY工坊-vX.Y.Z.zip` | 发行包 |
| `CY工坊-vX.Y.Z.zip.sha256` | 包校验值 |

WorkBuddy 的「CY工坊插件更新」技能读 `latest.json` 判断有没有新版，
下载后先校验 sha256 再替换，校验不过就不动现有安装。
