# Mid-Autumn Festival

An illustrated film about the legend, history, and meaning of Mid-Autumn: reunion, absence, and looking at the same Moon.

Watch the published film on [YouTube](https://www.youtube.com/watch?v=ouqWP7av0yg) or [Bilibili](https://www.bilibili.com/video/BV11Cpk6pEQM).

The final picture and voice edit lasts **8:26.00**, at **1920 x 1080, 25 fps**. It contains narration, a separate question voice, and two chapter bells. No background music is included.

## Open and edit

Open [MidAutumn.kdenlive](MidAutumn.kdenlive) in **Kdenlive 26.08.1 or later**. Keep `assets/` beside the project file. All media references are relative to this directory.

The picture uses two tracks: **Picture** holds the final scene images; **Dissolves** provides the opening fade, scene changes, and the Chang'e fade with native opacity keyframes. **Narration**, **Question**, and **Chapter bells** remain separate audio tracks. The scene timing, narration source offsets, and ending hold are preserved.

The project contains only final inputs: 77 scene images and four unchanged audio sources. Identical scene files are shared. Artwork, captions, and diagram states are retained in the final scene images; native fades can be edited directly in the timeline.

## Files

- [Native editing project](MidAutumn.kdenlive)
- [Final narration](narration.md), including its intentional Chinese wording
- [Plain-text English transcript](narration.txt), with romanized names as used in the English subtitle track
- [English and Simplified Chinese subtitles](subtitles/)
- [Final release thumbnail](publishing/thumbnail.jpg), used for both platforms
- [Asset manifest](asset-manifest.csv), with file sizes and SHA-256 checksums
- [Credits and licenses](CREDITS.md)

## Subtitles

| Language | Timed text | Styled captions | Plain text |
| --- | --- | --- | --- |
| English | [SRT](subtitles/narration-en.srt) | [ASS](subtitles/narration-en.ass) | [Transcript](narration.txt) |
| Simplified Chinese | [SRT](subtitles/narration-zh-Hans.srt) | [ASS](subtitles/narration-zh-Hans.ass) | [Translation](subtitles/narration-zh-Hans.txt) |

Both tracks contain 147 non-overlapping cues synchronized to the published 8:26 film. The English track retains the spoken Chinese closing lines and includes the separately recorded "The end." The Chinese track includes English alongside the two closing wishes.

Subtitle files are supplied separately from the native Kdenlive timeline. Use them as selectable tracks or as sources for an edition with captions burned into the picture. Retime them if you change the edit. The ASS files specify a 1920 x 1080 canvas and Microsoft YaHei; select another installed font with suitable Chinese glyphs if that font is unavailable.

The two bilingual closing wishes already appear in the scene images. Omit their subtitle cues when burning captions into this picture to avoid displaying them twice. Keep the complete tracks for standalone subtitle use.

## Render your version

Confirm the **HD 1080p 25 fps** profile, then use **File > Render** with an H.264/AAC MP4 preset. Render the full project rather than a short selected zone. Preserve the approximately five-second silent ending.

Rendered movies and delivery packages are distributed separately and excluded from Git. Source files contain the final native project and the media it actually references.
