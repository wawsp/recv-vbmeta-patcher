# 修补你的三星 Recovery 和 vbmeta 镜像

# 操作指南

1. Fork 本仓库。

2. 将你的 vbmeta.img.lz4 和 recovery.img.lz4 上传到 fork 后的仓库中。

3. 进入 “ Action ” 选项卡，然后执行工作流程。

4. 执行成功后，会生成patched-recovery-and-vbmeta.zip文件，解压后，会有miniAP.tar.md5，其中包含已修补的带 fastbootd 的 recovery 以及去除校验的 vbmeta。

5. 使用Odin刷入已修补文件。

# 提示

对于使用OneUI8.5的用户，需要先进入维护模式，从维护模式关机后，才能通过按键进入下载模式 （Download Mode ）。
