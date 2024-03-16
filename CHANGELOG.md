## 2024-03-16

### Added
- Support for Python 3.12 in CI environments.

### Changed
- Updated GitHub Actions workflow to remove scheduled triggers and use newer versions of actions.
- Refactored main tasks to use `ansible_facts['os_family']` for conditionals.
- Improved handling of reboots in CI environments by checking for GitHub Actions specifically.
- Removed molecule testing setup indicating a shift away from this testing strategy.

### Fixed
- Various fixes to ensure compatibility with newer environments and streamline CI processes.