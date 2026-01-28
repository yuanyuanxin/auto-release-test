# Changelog

All notable changes to this project will be documented in this file.

## [1.5.0] - 2026-01-19

### Added

- Real-time `joint_effort` reading via `IController.get_joint_actual_effort()`
- `joint_effort_limit` now supports read operations (previously write-only)
- Example: add `read_joint_effort_limit()` demo in `1.read.py`

### Changed

- Effort values use Ampere (A) units externally, with automatic mA conversion for firmware
- Renamed `current_limit` to `effort_limit` across all APIs

### Deprecated

- `current_limit` API - use `effort_limit` instead

## [1.1.0-rc1] - 2026-01-28

### Added
- 测试 prerelease 版本

## [1.0.0] - 2026-01-28

### Added
- 初始化项目
- 添加自动发布功能测试

### Changed
- 优化 README 文档

### Fixed
- 修复示例问题

### Removed
- 移除废弃的 API

## [0.9.0] - 2026-01-27

### Added
- 项目雏形
