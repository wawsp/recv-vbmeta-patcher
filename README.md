# 修补你的三星 Recovery 和 VBMeta 镜像

# 操作指南
1.Fork 本仓库。
2.将你的 vbmeta.img.lz4 和 recovery.img.lz4 上传到 fork 后的仓库中。
3.进入“Action”选项卡，然后执行工作流程。
4.执行成功后，会生成patched-recovery-and-vbmeta.zip的文件，解压后，会有miniAP.tar.md5，其中包含已修补的带 fastbootd 的 recovery 和 vbmeta。
只需使用Odin将已修补文件刷入AP即可。
