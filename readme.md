# Open Subtitles

## !WARNING!

(2020-11-10) The Open Subtitles API specifications have unexpectedly been changed. Thefore this library is currently not functioning with the API. A fix may be expected in the following days.

## 1. Open Subtitles library

This is a .Net Standard 2.0 client library implementation for the [REST API](https://www.opensubtitles.com/docs/api/html/index.htm) provided by [OpenSubtitles.com](https://opensubtitles.com).

### 1.1 Supported Open Subtitles API features

The following features are supported:

* [Authentication](https://www.opensubtitles.com/docs/api/html/index.htm#create-session-and-token)
* [Download subtitle file](https://www.opensubtitles.com/docs/api/html/index.htm#download-subtitle-file)
* [Find subtitles for a video file](https://www.opensubtitles.com/docs/api/html/index.htm#find-subtitles-for-a-video-file).
* [Get user data](https://www.opensubtitles.com/docs/api/html/index.htm#get-user-data)

On request the missing features can be implemented.

## 2. NuGet package

The [NuGet package](https://www.nuget.org/packages/OpenSubtitles) can be installed using the NuGet Package Manager:

```PM
Install-Package OpenSubtitles
```

## 3. Projects using Open Subtitles library

This following projects use this library:

* [Subtitle Downloader](https://github.com/michelvosje/SubtitleDownloader)
