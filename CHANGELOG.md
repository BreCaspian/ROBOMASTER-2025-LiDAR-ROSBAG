# 更新日志 / Changelog

本文件记录了项目的所有重要变更。

格式基于 [Keep a Changelog](https://keepachangelog.com/zh-CN/1.0.0/)，
并且本项目遵循 [语义化版本](https://semver.org/lang/zh-CN/)。

## [Unreleased]

### 新增 / Added
- 添加了开源相关文件，准备项目开源

### 变更 / Changed
- 更新了README.md，添加了许可证信息和贡献指南链接

### 修复 / Fixed
- 无

### 移除 / Removed
- 无

## [1.0.0] - 2025-08-07

### 新增 / Added
- 初始发布 ROBOMASTER-2025 LiDAR ROSBAG 数据集
- 包含两个高质量的LiDAR ROSBAG文件---通过链接下载：
  - `RM-LiDAR-ROSBAG_01.bag` (13分22秒, 11.2 GB)
  - `RM-LiDAR-ROSBAG_02.bag` (13分59秒, 12.9 GB)
- 详细的使用文档和说明
- 设备规格和技术参数说明
- 数据下载链接（百度网盘和Hugging Face）
- 可视化示例和GIF演示
- 完整的ROSBAG信息说明

### 技术规格 / Technical Specifications
- 使用镭神 CH128X1 激光雷达（128线）
- 点云话题：`/cloudpoints`
- 采样频率：10 Hz
- 数据格式：ROS 1 `.bag` 文件（未压缩）
- 探测距离：最远200m
- 点云速率：≈760,000点/秒

---

## 版本说明 / Version Notes

- **[Unreleased]**: 正在开发中的功能
- **[1.0.0]**: 首次正式发布

## 贡献指南 / Contributing

如果您想为此项目做出贡献，请查看我们的 [贡献指南](CONTRIBUTING.md)。
