![mmdl](mmdl_image.png)

# mmdl - Mega Music Downloader

![License](https://img.shields.io/pypi/l/mmdl?style=for-the-badge) ![PyPI](https://img.shields.io/pypi/v/mmdl?style=for-the-badge) ![Downloads](https://img.shields.io/pypi/dw/mmdl?style=for-the-badge)

## What is mmdl ❓

**TLDR**: MMDL is a cli app which allows you to quickly and efficiently download one or multiple songs from YouTube.

I wanted a tool to quickly and efficiently download songs/audios from YouTube based on the name of the song. I also wanted the songs to be tagged with metadata. This is why I created this simple to use tool.

### Why

- 🕖 Fast: Thanks to *async code* and *multithreading*.
- ⚡ Simple: Type `mmdl go`  and get started with downloading songs.
- ✨ Powerful
  - Find songs based on songs query/title
  - Skip already existing songs
  - Add metadata such as artist name and artwork

## Requirements 👇

- Python 3

- FFmpeg

  *Here is a quick guide: https://github.com/adaptlearning/adapt_authoring/wiki/Installing-FFmpeg*

## Install ❤️

*Make sure you have installed FFmpeg. Else this programm won’t work.*

```bash
pip install -U mmdl
```

⚡ **That’s it!** ⚡

Mmdl has been only been tested using Python 3.9. 
## Usage 🔥

### Go

*Very quick and easy way of running the cli. Few questions will be asked via prompts. **This is the recommended way!***

```shell
mmdl go
```

### Download

*Fast and traditional way of running the cli. Pass arguments and have your songs downloaded. Useful for automation scripts.*

```shell
mmdl download <method> #(add -h for more information)
```

#### Methods

- **File** `mmdl download file <location>`: Get songs from file. Then download them.
- **List** `mmdl download list "Term1" "Term2" ...` or `mmdl download list -a` for a prompt: Add multiple songs as cli arguments or enter them in a prompt.
- **YTMusic** (beta) `mmdl download ytmusi` : Download multiple songs from *YouTube Music liked songs playlist* (via parsing HTML)
- **Single** `mmdl download single song name`: Download a single song.

## Support ⚡

### Bugs 🐛

Please [open a issue](https://github.com/techboy-coder/mmdl/issues/new) with some information to reproduce your problem.

### Questions ❓

Please [start/search for a discussion](https://github.com/techboy-coder/mmdl/discussions/new). 

## Contributing 🤜

We welcome contributions very much (Even small ones). They are appreciated. 

### Steps

1. Check for bugs/issues you would like to solve or think of new features you would like to implement.
2. Fork the repo and make your changes.
3. Send a pull request.

## Credits 🥂

**The following amazing libraries helped me make this project:**

- https://github.com/tmbo/questionary - Questionary by Tom Bocklisch and Kian Cross
- https://github.com/alexmercerind/youtube-search-python - Youtube Search Python by Hiteh Kumar Saini
- https://github.com/willmcgugan/rich - Rich by Will McGugan
- https://github.com/ytdl-org/youtube-dl - YoutubeDl

## Legality ⚖️

**I assume no liability or responsibility for how this app is used.** Please stay legal and respect the laws in your country. This tool is intended for archiving music for which you have a license. 

## License 📜

The MIT License (MIT)

Copyright (c) 2021 - techboy-coder

------

