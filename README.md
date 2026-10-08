# Vancouver Regulation Toolkit

ARCH 540 Designing the Design (UBC SALA, Fall 2026), Assignment 1: fifteen student-built tools for Vancouver regulations, with each student's live demo from the review on October 2, 2026.

Page: https://genenv.github.io/arch540-a1-toolkit/

## Updating your entry

Each tool is one file in `projects/`, for example `projects/01_curbside.json`. Edit only your own file: open it on GitHub, click the pencil icon, change the text, and commit to `main`. The page rebuilds itself within a minute.

Fields:

- `tool`, `student`, `subtitle`: title line.
- `brief`: your own description of the tool, as written in the class deck.
- `tool_url`: the live tool. `repo_url`: your repository. `links`: extra links as `{"label": "...", "url": "..."}`. `tool_note`: a short note shown next to the links, for example when the tool has to be run locally.
- `video`: the demo video. Either a direct `.mp4` link, or a Google Drive share link (`https://drive.google.com/file/d/<id>/view`) whose sharing is set to "Anyone with the link". Drive links play in Drive's embedded player.
- `poster`: the thumbnail shown before the video plays (`img/<nn>_poster.jpg`); replace the image file to change it.
- `discussion`: the notes from the review discussion, one string per point.

Keep the JSON valid: strings in double quotes, commas between items, no trailing comma. If your file has a syntax error, only your entry shows an error message; the rest of the page still works.

`projects.json` lists the files in display order and holds the cross-cutting remarks. The first batch of demo videos is attached to the `v1` release of this repository.

## Links

- Class deck (each student's own slide): https://docs.google.com/presentation/d/1XPjtIx0U5lZmkpay939JMuhR1LfokV4nct9xl7CzXt8/edit?usp=sharing
- Comment form (the in-page comment boxes post to it): https://docs.google.com/forms/d/e/1FAIpQLSfrFx3kPWrOba2GXbBf4c7nvTuhs9LC45DHTB-zfcLDQGyZkg/viewform
