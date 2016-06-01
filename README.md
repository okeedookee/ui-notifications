# ui-notifications

<!-- TOC depthFrom:2 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [Maintenance Note](#maintenance-note)
- [Release Notes](#release-notes)

<!-- /TOC -->

## Maintenance Note
You can show users a maintenance note by adding a note the the [`content/maintenance.md`](https://github.com/instana/ui-notifications/blob/gh-pages/content/maintenance.md) file. You can use markdown in the file to format the note's content. We recommend that you keep formatting restricted to emphasizes of certain words and times for a consistent look and feel. The following shows the content of the `content/maintenance.md` could be and what the UI would render.

```markdown
There will be a maintenance for your environment from *10:00 UTC on*.
```

<p align="center">
  <img src="./sample-maintenance-note.png"
       alt="Screenshot showing a maintenance note"
       width="400px"
       align="center"/>
</p>

To remove the maintenance message, empty the `content/maintenance.md` file.


## Release Notes
Release notes will always be shown to users when the [`content/release-notes.md`](https://github.com/instana/ui-notifications/blob/gh-pages/content/release-notes.md) file is changed. You can use markdown in this file and there is no document size restriction. If you want to use links in the release notes file, you can do so. Just make sure that you use absolute links instead of relative ones. For instance, in order to reference a file `pic.png` which is located in the `content/files/` directory, use the link `/notifications/files/pic.png`.
