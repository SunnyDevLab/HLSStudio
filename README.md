# HLS Studio

**Professional HLS Video Archiving Workstation \| 专业 HLS
视频归档工作站**

HLS Studio is a Windows desktop application designed to help detect,
download, and archive compatible HLS and other media streams through a
dedicated desktop interface.

HLS Studio 是一款 Windows
桌面应用，旨在通过专用桌面界面，帮助用户检测、下载和归档兼容的 HLS
及其他媒体流。

> **Responsible use / 合法使用**
>
> Use HLS Studio only for content you own or are authorized to download
> or archive. Respect copyright, website terms, privacy, and applicable
> laws.
>
> 请仅将本软件用于你拥有或已获授权下载、归档的内容，并遵守版权规定、网站条款、隐私要求及适用法律。

## Features \| 主要功能

-   **Video stream detection / 视频流检测** --- Detect accessible video
    streams and media resources from supported pages.
-   **Concurrent downloads / 并发下载** --- Download media segments with
    adjustable concurrency.
-   **Compatible encrypted streams / 兼容的加密流** --- Process
    supported encrypted streams when the media source provides the
    required decryption keys.
-   **Direct video URLs / 直链视频** --- Download directly accessible
    progressive video files, such as MP4 or WebM.
-   **DASH and split audio/video / DASH 与音视频拆流** --- Basic DASH
    and separate audio/video tracks; merge with FFmpeg when available.
-   **Visible browser mode / 可见浏览器模式** --- Open a browser window,
    play a video manually, and capture the stream currently playing.
-   **Proxy and retry-friendly downloads / 代理与断点续下** --- Optional
    HTTP proxy and the ability to skip already-downloaded segments when
    retrying.
-   **Desktop task management / 桌面任务管理** --- Manage page URLs,
    output paths, progress, and logs in one Windows interface.

## How to Use \| 使用方法

1.  Launch HLS Studio and open the main workspace.\
    启动 HLS Studio，进入主工作界面。
2.  Paste the URL of a video page you are authorized to download or
    archive.\
    粘贴你有权下载或归档的视频页面地址。
3.  Optionally configure an HTTP proxy and the number of concurrent
    download workers.\
    按需配置 HTTP 代理和并发下载数。
4.  If the site requires manual playback, login, or CAPTCHA completion
    before media requests appear, enable visible browser mode.\
    如果网站需要手动播放、登录或完成验证码后才会出现媒体请求，请启用可见浏览器模式。
5.  Choose the output folder and file name, then start the download.\
    选择输出目录和文件名，然后开始下载。
6.  Monitor progress and logs. You can cancel a running task when
    needed.\
    查看任务进度和日志；必要时可以取消正在运行的任务。

### Visible browser mode \| 可见浏览器模式

Play the desired video in the opened browser window, then click
**Download Playing Video** at the top of the page. Keep the browser open
if you want to switch videos and capture more streams. Close it when
finished.

在弹出的浏览器窗口中播放目标视频，然后点击页面顶部的 **Download Playing
Video（下载正在播放的视频）**。如需切换视频并继续捕获，请保持浏览器打开；完成后再关闭窗口。

## Security and Antivirus \| 安全与杀毒软件

HLS Studio is an independently developed Windows application. Newly
packaged desktop applications and bundled components may sometimes
trigger antivirus or Windows SmartScreen warnings. A warning does not by
itself prove that a file is malicious, but it should be taken seriously.

HLS Studio 是独立开发的 Windows
应用。新打包的桌面程序及其附带组件有时可能触发杀毒软件或 Windows
SmartScreen 提示。安全提示本身并不能证明文件一定有恶意，但仍应认真对待。

If the application does not open or a bundled file appears to be
missing:

1.  **Verify the source.** Download only from a release source you
    trust; avoid unknown re-uploads.
2.  **Check protection history.** Review Windows Security or your
    antivirus quarantine and note the detection name and file path.
3.  **Verify before restoring.** Restore a quarantined file only after
    you have independently verified that the package is trustworthy.
4.  **Use caution with exclusions.** If you trust the verified package,
    consider a narrowly scoped folder or file exclusion rather than
    disabling antivirus protection entirely.
5.  **Review SmartScreen warnings carefully.** Do not bypass warnings
    unless you trust the source and understand the risk.
6.  **Report possible false positives.** Keep the detection name,
    application version, and file hash for investigation.

**Do not disable antivirus protection entirely. Do not restore or run
files from an untrusted source.**

如果程序无法启动或附带文件疑似丢失：

1.  **确认来源。**
    仅从可信的发布渠道下载，避免使用来历不明的二次上传文件。
2.  **查看防护记录。** 检查 Windows
    安全中心或杀毒软件隔离区，并记录检测名称和文件路径。
3.  **恢复前先核验。**
    只有在独立确认安装包可信后，才考虑恢复被隔离的文件。
4.  **谨慎设置排除项。**
    如果已确认文件可信，可考虑仅对指定文件或安装目录设置排除项，不要彻底关闭杀毒软件。
5.  **认真对待 SmartScreen 提示。**
    只有在确认来源可信且理解风险后，才考虑继续运行。
6.  **反馈可能的误报。**
    保存检测名称、软件版本和文件哈希，以便进一步核查。

**请勿彻底关闭杀毒软件，也不要恢复或运行来自不可信来源的文件。**

## Network Proxy \| 网络代理

An HTTP proxy is optional. Configure it only if your network requires
one. For example, a local proxy might use `http://127.0.0.1:7890`; the
actual address and port depend on your proxy application.

HTTP 代理是可选项，仅在网络环境需要时配置。例如，本地代理可能使用
`http://127.0.0.1:7890`，实际地址和端口以你的代理软件设置为准。

## Feedback \| 反馈

Feedback and suggestions are welcome, especially about challenges in
video downloading and archiving, useful workflow improvements, and
features that would make HLS Studio better.

欢迎反馈使用在线视频下载与归档时遇到的问题、能够改善工作流程的功能建议，以及对
HLS Studio 的改进意见。

------------------------------------------------------------------------

**HLS Studio --- Professional Video Archiving Workstation**\
**HLS Studio --- 专业视频归档工作站**
