Assets for [Encapsul8](https://github.com/ElectricR/Encapsul8)

### Made with
```sh
wf-recorder -g "<x>,<y> 444x218" -r 60 -c ffv1
ffmpeg -i recording.mkv -vf "fps=30" -c:v libwebp -lossless 1 -loop 0 -ss "00:00:0?.00" -t "00:00:0?.00" output.webp
```
