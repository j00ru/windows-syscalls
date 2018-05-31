# Windows System Call Tables

The repository contains system call tables collected from all modern and most older releases of Windows, starting with Windows NT.

Both 32-bit and 64-bit builds were analyzed, and the tables were extracted from both the core kernel image (`ntoskrnl.exe`) and the graphical subsystem (`win32k.sys`).

## Formats

The data is formatted in the CSV and JSON formats for programmatic use, and as an HTML table for manual inspection.

The HTML files are also hosted on my blog under the following links:

- `ntoskrnl.exe`, x86: http://j00ru.vexillium.org/syscalls/nt/32/
- `ntoskrnl.exe`, x64: http://j00ru.vexillium.org/syscalls/nt/64/
- `win32k.sys`, x86: http://j00ru.vexillium.org/syscalls/win32k/32/
- `win32k.sys`, x64: http://j00ru.vexillium.org/syscalls/win32k/64/

## Operating systems

The following major versions of Windows are included in the tables:

| System              | x86 versions                       | x64 versions                       |
|---------------------|------------------------------------|------------------------------------|
| Windows NT          | SP3, SP4, SP5, SP6                 | –                                  |
| Windows 2000        | SP0, SP1, SP2, SP3, SP4            | –                                  |
| Windows XP          | SP0, SP1, SP2, SP3                 | SP1, SP2                           |
| Windows Server 2003 | SP0, SP1, SP2, R2, R2 SP2          | SP0, SP2, R2, R2 SP2               |
| Windows Vista       | SP0, SP1, SP2                      | SP0, SP1, SP2                      |
| Windows Server 2008 | SP0, SP2                           | SP0, SP2, R2, R2 SP1               |
| Windows 7           | SP0, SP1                           | SP0, SP1                           |
| Windows Server 2012 | –                                  | SP0, R2                            |
| Windows 8           | 8.0, 8.1                           | 8.0, 8.1                           |
| Windows 10          | 1507, 1511, 1607, 1703, 1709, 1803 | 1507, 1511, 1607, 1703, 1709, 1803 |

Windows Server 2016 and later are not included, as their syscall tables are equivalent to that of Windows 10:

| Windows Server version | Windows 10 release |
|:----------------------:|:------------------:|
|          2016          |        1607        |
|          1709          |        1709        |
|          1803          |        1803        |

## Thanks

We would like to thank the following contributors to the project: Woodmann, Deus, Gynvael Coldwind, MeMek, Alex, Omega Red, Wandering Glitch.

## Contact

Mateusz 'j00ru' Jurczyk (j00ru.vx@gmail.com)
