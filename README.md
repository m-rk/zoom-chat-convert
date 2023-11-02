# Zoom Chat Convert

Converts Zoom's chat `.txt` format to subtitle `.srt` format.

Zoom's chat format:

```
00:01:17	Mark Davies:	Here are some chat messages
00:02:34	Mark Davies:	Like you'd see in Zoom.
00:04:05	Mark Davies:	But what if we could take these
00:06:50	Mark Davies:	And display them as subtitles?
```

Subtitle .srt format:

```
1
00:01:17,000 --> 00:01:27,000
Mark Davies: Here are some chat messages

2
00:02:34,000 --> 00:02:44,000
Mark Davies: Like you'd see in Zoom.

3
00:04:05,000 --> 00:04:15,000
Mark Davies: But what if we could take these

4
00:06:50,000 --> 00:07:00,000
Mark Davies: And display them as subtitles?
```