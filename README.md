# Scient Desktop Beta

This repository holds Scient Desktop Beta installers and update manifests.
[Source code and stable releases](https://github.com/ScientFactory/scient-desktop)
remain in the canonical Scient repository.

Beta releases preview upcoming changes for users who choose the Beta update
track. Stable and Beta use the same application and saved data. Switching back
to Stable waits until a stable version is at least as new as the installed Beta.

Qualified installers will appear on the
[Releases page](https://github.com/ScientFactory/scient-desktop-beta/releases).
The repository is initially empty of releases while the channel is being
qualified. No Beta artifacts are published into the stable release feed.

Each release includes an immutable `scient-release-handoff.json` containing the
actual source commit and tree, distribution channel, and artifact hashes.
Tags in this artifact repository identify distribution records; they do not
identify source commits. Development and bug reports belong in the source
repository.
