<div align = center>

<h1>EROFS For 4.9 Kernel</h1>

![License](https://img.shields.io/static/v1?label=License&message=BY-NC-SA&logo=creativecommons&color=green)
![Language](https://img.shields.io/github/languages/top/Renzprjkt/RecoveryCI)
![Issues](https://img.shields.io/github/issues/Renzprjkt/RecoveryCI)
![Pull Requests](https://img.shields.io/github/issues-pr/Renzprjkt/RecoveryCI)
<br>

How To Use?
<br>

</div>

# How to Use
1. just add erofs to the kernel in "fs"

2. and don't forget to activate the erofs function in defconfig :

   CONFIG_EROFS_FS=y

   CONFIG_EROFS_FS_PCPU_KTHREAD=y

   CONFIG_EROFS_FS_PCPU_KTHREAD_HIPRI=y
