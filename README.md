# Platforms description for Airos

The platform in the Airos system is a comprehensive set of libraries, tools, and other resources that define the system's working environment. Each platform is created with the aim of providing the latest features and capabilities that may be impossible to implement in previous versions. This allows users to enjoy innovative solutions and optimal performance that meet their growing needs.

However, it is important to understand that it is always necessary to use the latest available platform, which delays the need for reinstallation of the system. Default Airos installers always use the latest platform, providing users with access to the most current features and security measures.

## Current platforms
✅ - Full support

🟡 - Partial support/might depend on hardware

🔴 - No support

| Name       | Release date | EOL | State | Architecture | SELinux | TPM | Bootloader     | Kernel | Rootfs       |
|------------|--------------|-----|-------|--------------|---------|-----|----------------|--------|--------------|
| Swan       | -            | -   | WIP   | AMD64        | ✅       | ✅   | UEFI           | 6.8.2  | brtfs (LUKS) |
| Strawberry | -            | -   | WIP   | AArch64      | ✅       | 🔴   | Raspberry Pi 4 | 6.8.2  | brtfs        |
| Chestnut   | -            | -   | WIP   | AMD64        | 🟡       | 🔴   | Legacy         | 6.8.2  | ext4         |

### Planned platforms
Blueberry - for Raspberry Pi 5

Raspberry Pi 5 should work correctly on Strawberry, but there is no optimization and support for new hardware features added in Raspberry Pi 5.
