# Mid-Autumn Project

Editable source projects for illustrated films about Mid-Autumn legends, traditions, and culture.

Each film has its own directory under `videos/`, containing its final native editing project, required media, narration, subtitles, release artwork, and credits. This lets several films live in one repository while keeping their timelines and project settings independent.

## Films

| Film | Source project | Watch |
| --- | --- | --- |
| Mid-Autumn Festival | [Project guide](videos/01-mid-autumn-festival/README.md) / [Kdenlive project](videos/01-mid-autumn-festival/MidAutumn.kdenlive) | [YouTube](https://www.youtube.com/watch?v=ouqWP7av0yg) / [Bilibili](https://www.bilibili.com/video/BV11Cpk6pEQM) |

The first film lasts **8:26**, at **1080p, 25 fps**, with English narration and no background music. English and Simplified Chinese subtitle sources are included. Finished video files are hosted separately from the source repository.

## Open a project

Clone the repository, including its published source history:

```sh
git clone https://github.com/sunheat/mid-autumn-project.git
```

Open the `.kdenlive` file in the relevant video directory using Kdenlive 26.08.1 or later. Keep each project's media beside its project file; media references use paths relative to that directory.

Read the film's project guide for editing, subtitles, and rendering details. Final images, audio, subtitle files, and release artwork are included where their reuse conditions allow. Movies, delivery ZIP files, caches, and automatic editor backups are excluded from Git.

## Add another film or reuse artwork

Create a new directory under `videos/` for each additional film. Keep its project file, media, narration, creative notes, and credits together. A project-specific asset belongs in that film's directory.

When an asset is actually used by more than one film, move it into a `shared/` directory and relink both projects to it using relative paths. Retain its source and license information. Avoid duplicating a shared master or moving media without updating its project references. Independent project directories and relative media links keep Kdenlive projects separate.

## License and attribution

Original creative contributions are licensed under [CC BY 4.0](LICENSE), to the extent the contributor holds the relevant rights. Third-party materials retain their own licenses and attribution requirements; see each film's `CREDITS.md` before reusing photographs, composites, or sound recordings.

AI-assisted illustrations and synthesized voices are described in the film's [credits](videos/01-mid-autumn-festival/CREDITS.md). Generated illustrations are not documentary photographs.
