- concat multiple video files from m3u8 playlist is

```
ffmpeg -i "<playlist>" -codec copy output.mp4
```

```
ffmpeg -i "<playlist>" -c copy -bsf:a aac_adtstoasc output.mp4
```

- convert .ts to .mp4

```
ffmpeg -i all.ts -vcodec libx264 -acodec aac output.mp4
```
