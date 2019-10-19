# Add new song

If you are ready for pull your beatmap into demo beatmap repo, please follow some rules.

## Contain file

You can check [demo file](https://github.com/osu-Karaoke/sample-beatmap/tree/master/v1/%E3%82%B7%E3%83%A3%E3%82%A4%E3%83%8B%E3%83%B3%E3%82%B0%E3%82%B9%E3%82%BF%E3%83%BC), the complete resource file should like : 

- `Beatmap.osu` : osu beatmap(text file).
- `README.md` : descript song info.
- `bg.png` : background image.
- `lyric.lrc` : raw lyric file with `timetag` and `ruby(optional)`.
- `lyric.txt` : raw lyric text file.
- `song.mp3` song file.

Optional : 

- `song-karaoke.mp3` song without vocal, might be use in the future.
- `video.mp4` video in gameplay.

.

## Fill info

Title should like : 

```
[NewSong]SongName
```

And please add the following info to your content

```
Name : 
Author : 
Singer : 
Url : 
BeatmapVersion : 
Relative issue : 
.
- [ ] This song has no copyright issue.
```

Then  change `[ ]` into `[x]` to agree some rules

.

## To admin

1. Add `[Authorized]` tag if user guarantee that this song has no copyright issue in demo use.

2. Remember to add tag `[New song]` `[Complete]`(when you complete this beatmap) also.
