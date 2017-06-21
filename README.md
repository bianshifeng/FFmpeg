FFmpeg README
=============

FFmpeg is a collection of libraries and tools to process multimedia content
such as audio, video, subtitles and related metadata.
FFmpeg 是一个用来处理多媒体内容的工具和库集合，多媒体内容包括音频、视频、字幕已经相关的数据元信息
## Libraries

* `libavcodec` provides implementation of a wider range of codecs.
* 该库实现了对多种视频格式的解码
* `libavformat` implements streaming protocols, container formats and basic I/O access.
* 该库实现对视频流协议、视频解码格式和视频数据传输通道的格式化处理
* `libavutil` includes hashers, decompressors and miscellaneous utility functions.
* 该库提供视频编解码的一些通用功能，包括： 哈希校验、数据包解压以及其它功能
* `libavfilter` provides a mean to alter decoded Audio and Video through chain of filters.
* 
* `libavdevice` provides an abstraction to access capture and playback devices.
* `libswresample` implements audio mixing and resampling routines.
* `libswscale` implements color conversion and scaling routines.

## Tools

* [ffmpeg](https://ffmpeg.org/ffmpeg.html) is a command line toolbox to
  manipulate, convert and stream multimedia content.
* [ffplay](https://ffmpeg.org/ffplay.html) is a minimalistic multimedia player.
* [ffprobe](https://ffmpeg.org/ffprobe.html) is a simple analysis tool to inspect
  multimedia content.
* [ffserver](https://ffmpeg.org/ffserver.html) is a multimedia streaming server
  for live broadcasts.
* Additional small tools such as `aviocat`, `ismindex` and `qt-faststart`.

## Documentation

The offline documentation is available in the **doc/** directory.

The online documentation is available in the main [website](https://ffmpeg.org)
and in the [wiki](https://trac.ffmpeg.org).

### Examples

Coding examples are available in the **doc/examples** directory.

## License

FFmpeg codebase is mainly LGPL-licensed with optional components licensed under
GPL. Please refer to the LICENSE file for detailed information.

## Contributing

Patches should be submitted to the ffmpeg-devel mailing list using
`git format-patch` or `git send-email`. Github pull requests should be
avoided because they are not part of our review process and will be ignored.
