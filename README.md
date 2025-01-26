# Btrfs Snapshot Backup Script

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![GitHub Issues](https://img.shields.io/github/issues/yourusername/yourrepository)](https://github.com/yourusername/yourrepository/issues)
[![GitHub Stars](https://img.shields.io/github/stars/yourusername/yourrepository)](https://github.com/yourusername/yourrepository/stargazers)

**中文 | [English](#english)**

<p align="center">
  <img src="https://placehold.co/200x200/DCDCDC/000000?text=Logo" alt="Project Logo" width="150">
</p>

## Btrfs 自动快照系统

这个仓库包含两种版本的 Btrfs 快照备份脚本：**精简版** 和 **小白完全版**，旨在简化 Btrfs 快照的管理，并提供增强的功能和易用性。

### 一. 精简版：

*   **特点：** 单个脚本文件，专注于快照的创建、恢复和删除。
*   **适用场景：** 适合对 Btrfs 快照有一定了解，需要简单快捷操作的用户。

### 二. 小白完全版：

*   **特点：** 多脚本文件，提供更全面的功能和更友好的用户体验。
*   **适用场景：** 适合对 Btrfs 快照不熟悉，但需要自动化备份和管理的用户。

## Btrfs 自动快照系统小白部署指南

**重要提示：** 以下操作需要在 Linux 系统的终端 中进行。终端就像是 Linux 系统的命令控制台，您需要通过输入命令来操作计算机。

### 功能列表：

*   ✅ **智能电源状态检测：** 仅在交流电源连接时进行备份，可通过配置更改。（可配置）
*   🔒 **原子级进程锁：** 防止脚本重复执行，确保备份过程稳定。
*   🔁 **快照创建失败自动重试：**  创建失败自动重试最多 3 次，提高成功率。
*   📢 **智能 GUI/终端 通知：** 自动选择合适的通知方式（GUI 或终端）。
*   🛠️ **错误自动回滚：** 可选配置，出现错误时回滚快照，保障数据安全。同时提供详细日志记录。
*   📅 **全自动定时任务：** 每天自动备份，无需手动干预。
*   🧹 **智能清理旧快照：** 根据设置自动删除旧的快照，节省磁盘空间。
*   ⚙️ **灵活配置选项：** 可自定义许多设置，满足不同的备份需求。
*   🛡️ **增强的脚本健壮性和安全性：** 脚本更加稳定可靠，同时确保系统安全。
*   💾 **磁盘空间智能检查：** 在备份前检查磁盘空间，避免磁盘空间不足导致备份失败。
*   📝 **日志自动轮转：** 自动管理日志文件，避免日志文件过大。
*   🔐 **完整的权限检查：** 确保脚本在适当的权限下运行，保障系统安全。

### 安装和使用

具体的安装和使用方法请参考以下链接：

*   [精简版安装指南](path/to/simple/install/guide.md)
*   [小白完全版安装指南](path/to/full/install/guide.md)
*   [配置文件说明](path/to/config/guide.md)

### 贡献

欢迎任何形式的贡献，包括但不限于：

*   提交 Bug 报告
*   提交功能请求
*   提交代码改进
*   撰写文档

请查看我们的 [贡献指南](path/to/contributing.md) 了解更多信息。

### 许可证

本项目基于 MIT 许可证进行开源。详细信息请查看 [LICENSE](LICENSE) 文件。

### 联系方式

如果您有任何问题或建议，请在 GitHub 上提交 issue 或联系：[your.email@example.com](mailto:your.email@example.com)

<br>
<br>

<a name="english"></a>
# Btrfs Snapshot Backup Script

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![GitHub Issues](https://img.shields.io/github/issues/yourusername/yourrepository)](https://github.com/yourusername/yourrepository/issues)
[![GitHub Stars](https://img.shields.io/github/stars/yourusername/yourrepository)](https://github.com/yourusername/yourrepository/stargazers)

**English | [中文](#中文)**

<p align="center">
  <img src="https://placehold.co/200x200/DCDCDC/000000?text=Logo" alt="Project Logo" width="150">
</p>

## Btrfs Automatic Snapshot System

This repository contains two versions of Btrfs snapshot backup scripts: the **Minimalist Version** and the **Beginner-Friendly Version**, designed to simplify the management of Btrfs snapshots, and provide enhanced functionality and ease of use.

### I. Minimalist Version:

*   **Features:** Single script file focused on creating, restoring, and deleting snapshots.
*   **Use Case:** Suitable for users who have a basic understanding of Btrfs snapshots and need simple and quick operations.

### II. Beginner-Friendly Version:

*   **Features:** Multiple script files offering comprehensive functionality and a user-friendly experience.
*   **Use Case:** Suitable for users who are not familiar with Btrfs snapshots but need automated backup and management.

## Btrfs Automatic Snapshot System Beginner's Deployment Guide

**Important Note:** The following operations need to be performed in the terminal of a Linux system. The terminal is like a command console for Linux system, and you will need to enter commands to operate the computer.

### Feature List:

*   ✅ **Intelligent Power State Detection:** Backup only when AC power is connected (configurable).
*   🔒 **Atomic Process Lock:** Prevents duplicate script execution, ensuring stable backups.
*   🔁 **Automatic Retry on Snapshot Creation Failure:** Automatically retries up to 3 times if creation fails.
*   📢 **Intelligent GUI/Terminal Notification:** Automatically selects the appropriate notification method (GUI or terminal).
*   🛠️ **Automatic Error Rollback:** Optional configuration to roll back snapshots on errors, ensuring data security. Also provides detailed logging.
*   📅 **Fully Automated Scheduled Tasks:** Automatically backs up daily, requiring no manual intervention.
*   🧹 **Intelligent Cleanup of Old Snapshots:** Automatically deletes old snapshots based on settings, saving disk space.
*   ⚙️ **Flexible Configuration Options:** Highly customizable settings to meet different backup needs.
*   🛡️ **Enhanced Script Robustness and Security:** Ensures a more stable and reliable script while maintaining system security.
*   💾 **Intelligent Disk Space Check:** Checks disk space before backups to prevent failures due to insufficient space.
*   📝 **Automatic Log Rotation:** Automatically manages log files, preventing them from becoming too large.
*   🔐 **Complete Permissions Check:** Ensures the script runs with appropriate permissions, maintaining system security.

### Installation and Usage

For detailed installation and usage instructions, please refer to the following links:

*   [Minimalist Version Installation Guide](path/to/simple/install/guide.md)
*   [Beginner-Friendly Version Installation Guide](path/to/full/install/guide.md)
*   [Configuration File Explanation](path/to/config/guide.md)

### Contributing

Contributions are welcome in any form, including but not limited to:

*   Submitting bug reports
*   Submitting feature requests
*   Submitting code improvements
*   Writing documentation

Please check our [Contribution Guidelines](path/to/contributing.md) for more information.

### License

This project is open-sourced under the MIT License. Please see the [LICENSE](LICENSE) file for details.

### Contact

If you have any questions or suggestions, please submit an issue on GitHub or contact: [your.email@example.com](mailto:your.email@example.com)
