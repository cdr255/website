---
layout: page
title: ChangeLog
permalink: /changelog/
---


# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog][001], though this project
does not really adhere to [Semantic Versioning][002] because it's
really just a poster used to collect static content and doesn't have a
concievable "API" at all aside from TCP itself.

## [Unreleased]

## [2.0.0] - 2018-01-28

### Added

- Recreated entire site from production after losing un-backed-up repo
	on Briar.
- Required Repo Files (ChangeLog, AUTHORS, README.md, LICENSE,
  INSTALL) now exist in repo.
- libfileio, mpdburn, and ripalbum now listed in [Software][]

### Changed

- All category pages (ie, those in the navbar) are permalinked as
  `/page/`, instead of as `/page.html`.
- The site is now built using [Jekyll][003] instead of [HarpJS][004],
  as per the relevant [Blog Post][005].
- [Recordings][] has Soundcloud above Bandcamp, fixed formatting.
- Removed the defunct [Flattr][006] button from the homepage.
- Migrated "Recent Changes" to this ChangeLog page.
- Updated Microbuttons to match what I currently use.
- Updated Some Dead/Obsolete Links Across the Site.

### Removed

- Old, Outdated Descriptions and References from pre-2017.
- **Fiction > Writing Credits** entirely, since it was still empty.
- [Recordings][] no longer lists the empty-since-2016 "Live
  Recordings" section.
- Defunct [Flattr][006] button from sidebar.
- Empty Leadsheets section on [Lessons][].
- Long Dead Games from [Games][].
- Empty Dread Section fron [Logs][].

[Games]: /games/
[Lessons]: /lessons/
[Logs]: /logs/
[Recordings]: /recordings/
[Software]: /software/
[001]: http://keepachangelog.com/en/1.0.0/
[002]: http://semver.org/spec/v2.0.0.html
[003]: https://jekyllrb.com/
[004]: http://harpjs.com/
[005]: http://www.toftandtoddy.com/2018/01/28/grounded-by-rubies/
[006]: https://flattr.com/

<!-- Local Variables: -->
<!-- mode: markdown   -->
<!-- End: -->