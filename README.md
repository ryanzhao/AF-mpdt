# AF-MPD Thruster

本仓库用于整理 AF-MPD（Applied-Field Magnetoplasmadynamic）thruster 原型的 CAD 资产、项目图片、测试资料与项目说明文档。

## 项目资料

- 项目完整描述：[`docs/project-description.md`](docs/project-description.md)
- CAD 渲染图 / 设计资产：[`images/cad-renders/`](images/cad-renders/)
- 测试平台照片：[`images/testing/`](images/testing/)
- 项目总览图、海报图、系统结构图：[`images/project-overview/`](images/project-overview/)

## 图片与资产目录约定

| 用途 | 目录 | 示例内容 |
| --- | --- | --- |
| CAD 渲染图 | `images/cad-renders/` | thruster 装配渲染图、喷管/阳极/阴极渲染图、制造图、当前 CAD 资产 |
| 测试平台照片 | `images/testing/` | vacuum chamber 安装照片、test platform 照片、点火测试照片 |
| 项目总览图 | `images/project-overview/` | 项目海报、系统结构图、总体装配图、流程图 |

> 说明：当前仓库已有 STEP、STL、3MF 与 PDF 设计文件已集中整理到 `images/cad-renders/`。后续如果导出 PNG/JPG/WebP 等渲染图，也应继续放入该目录。

## 系统组成概览

AF-MPD thruster 测试系统建议按以下模块组织：

1. **Thruster**：阴极、阳极喷口、导电板、夹具、分隔件与磁体支架。
2. **Vacuum chamber**：为点火与放电测试提供低压环境。
3. **Test platform**：固定 thruster，并承载供气、供电和测量接口。
4. **Control panel**：集中控制供电、推进剂流量、触发、仪表读数与安全联锁。
5. **Frame**：支撑真空舱、控制面板和测试平台等硬件。

更多项目动机、工作原理、设计迭代、测试方法、当前结果和未来改进方向见 [`docs/project-description.md`](docs/project-description.md)。

## 后续补充建议

- 在 `images/project-overview/` 添加系统结构图、项目海报和总体装配图。
- 在 `images/testing/` 添加真空舱、测试平台、控制面板和点火测试照片。
- 在 `images/cad-renders/` 添加从 CAD 软件导出的高分辨率渲染图，并保留必要的设计源文件。
- 在 `docs/` 中继续添加测试报告、BOM、装配步骤和安全检查清单。
