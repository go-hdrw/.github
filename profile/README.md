**go-hdrw** is a Go library designed for reading, parsing, and interacting with raw disk data and file systems. Inspired by proprietary libraries like `libhdrw`, it allows developers to work directly with block devices, access raw partitions, and explore file systems at a low level.

## Features

- **Raw Disk Access**: Directly interact with physical or virtual disks.
- **File System Parsing**: Analyze and extract data from different file systems (NTFS, FAT, ext4, etc.).
- **Partition Management**: Inspect and manipulate disk partitions.
- **Cross-Platform**: Supports major operating systems (Linux, Windows, macOS).
- **Read-Only Mode**: Safely read raw disk data without modifying the source.

## Use Cases

- **Data Recovery**: Extract lost or corrupted data from raw disk partitions.
- **Disk Inspection**: Inspect the structure of disks, including sectors and file systems.
- **File System Forensics**: Analyze disk images and explore file system metadata.
- **Custom File System Tools**: Build utilities to work with specific file systems or raw disk data.

## File System Support

- **NTFS**: Read metadata and files from NTFS partitions.
- **FAT32**: Access files and directory structures.
- **ext4**: Support for common Linux file systems.
- More file systems will be supported in future releases.
