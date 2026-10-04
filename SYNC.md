# 自动同步镜像

本仓库为 [librespeed/speedtest-go](https://github.com/librespeed/speedtest-go) 的自动同步镜像。

- 由 GitHub Actions 每 6 小时自动检查上游更新（workflow: `.github/workflows/sync-upstream.yml`）
- 自动同步：代码（master 分支）、tags、以及全部 Releases（含二进制安装包 assets）
- 也可在 Actions 页面手动触发（Run workflow）

不要直接在此仓库提交对上游文件的修改，同步时会以上游为准。
