# codeengn.com BASIC 01

Q. HDD를 CD-Rom으로 인식시키기 위해서는 GetDriveTypeA의 리턴값이 무엇이 되어야 하는가



A. 

| Return code/value       | Description                              |
| ----------------------- | ---------------------------------------- |
| **DRIVE_UNKNOWN**/0     | The drive type cannot be determined.     |
| **DRIVE_NO_ROOT_DIR**/1 | The root path is invalid; for example, there is no volume mounted at the specified path. |
| **DRIVE_REMOVABLE**/2   | The drive has removable media; for example, a floppy drive, thumb drive, or flash card reader. |
| **DRIVE_FIXED**/3       | The drive has fixed media; for example, a hard disk drive or flash drive. |
| **DRIVE_REMOTE**/4      | The drive is a remote (network) drive.   |
| **DRIVE_CDROM**/5       | The drive is a CD-ROM drive.             |
| **DRIVE_RAMDISK**/6     | The drive is a RAM disk.                 |

정답은 5