# Sermonship

Sermonship is a free Mac app that turns a recording of a sermon into a transcript, summaries,
discussion questions, daily devotionals, quote cards and vertical highlight clips — on your own
Mac, with nothing uploaded anywhere.

**Download:** the latest version is on the [Releases page](https://github.com/Nice-Take/sermonship-releases/releases/latest)
(`Sermonship-x.y.z.dmg`). Open the image, drag Sermonship to Applications, open it.

## What you need

- A Mac with Apple silicon (M1 or later) running macOS 14 Sonoma or newer.
- 16 GB of memory for the Standard writing model, 24 GB for the Advanced one (a Mac with less
  can write with your own Google Gemini key instead — the app explains this when it starts).
- The first time, Sermonship downloads its writing model once (6.4 GB or 15.6 GB). After that it
  works offline and starts straight away.

## Updates

Sermonship checks here for new versions and offers to install them (Sermonship menu › Check for
Updates…). Your sermons live in `~/Documents/Sermonship/` and are never touched by an update.

## Questions, problems, ideas

Open an [issue](https://github.com/Nice-Take/sermonship-releases/issues). If something went wrong,
attach the log: in Sermonship choose **Help › Show Logs** and add `Sermonship.log`, and the
`log.txt` from inside the sermon's folder if a particular sermon failed.

## Licence

Sermonship is free to use under the [Sermonship Licence](https://github.com/Nice-Take/sermonship-releases/blob/main/LICENSE.md);
the licence and the acknowledgements for the software it is built on are also in the app under Help.

---
This repository holds only the installers, the update feed (`appcast.xml`) and release notes.
