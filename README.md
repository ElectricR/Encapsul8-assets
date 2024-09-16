Assets for [Encapsul8](https://github.com/ElectricR/Encapsul8)

### Made with


```sh
wf-recorder -g "<x>,<y> 444x218" -r 60 -c ffv1

# Lossless:
ffmpeg -i recording.mkv -vf "fps=30" -c:v libwebp -lossless 1 -loop 0 -ss "00:00:0?.00" -t "00:00:0?.00" output.webp

# Lossy:
ffmpeg -i recording.mkv -vf "fps=30" -c:v libwebp -loop 0 -ss "00:00:0?.000" -t "00:00:0?.0" -vf "eq=brightness=0.05:contrast=1.1:saturation=1.2" output2.webp
```
