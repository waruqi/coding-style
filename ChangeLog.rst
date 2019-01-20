Change Log
===============================================================================

What is changelog?
-------------------------------------------------------------------------------

A change log is a file which contains a curated, chronologically ordered list
of notable changes for each version of a project.

Why keep changelog?
-------------------------------------------------------------------------------

To make it easier for users and contributors to see precisely what notable
changes have been made between each release or version of a project.

Who needs changelog?
-------------------------------------------------------------------------------

People do. Whether consumers or developers, the end users of software are
human beings who care about what's in the software. When the software changes,
people want to know why and how.

What may changelog file be named?
-------------------------------------------------------------------------------

``CHANGELOG.md``or ``CHANGELOG`` is the best convention so far.

What makes good changelog?
-------------------------------------------------------------------------------

A good `CHANGELOG.md <../CHANGELOG.md>`_ maybe following principles:

- The latest version comes first, which is newest version on top.

- Mention whether you follow `Semantic Versioning <http://semver.org/>`_.

- There should be an entry for every single version.

- The same types of changes for each version should be grouped.

- Versions and sections should be linkable, hence `Markdown <https://daringfireball.net/projects/markdown/>`_ over plain text.

- It's made for humans, not machines, so legibility is crucial.

- All date time in `YYYY-MM-DD HH:MM:SS ZZZZZ <https://www.iso.org/iso-8601-date-and-time-format.html>`_ format.

  * Like ``2012-06-02 18:15:15 +0800`` for ``18:15:15, June 2nd, 2012, +0800``.

Types of changes should following:

- ``Security`` for anything related with vulnerabilities and security.

- ``Added`` for any notable things new added.
- ``Fixed`` for any bug fixes.
- ``Changed`` for any notable changes in existing functionality.

- ``Preview`` for something which is preview or working in process.
- ``Deprecated`` for features which are soon-to-be removed.

How to minimize the effort to maintain changelog?
-------------------------------------------------------------------------------

- Keep an ``Unreleased`` section at the top to track the upcoming changes.
- People can see what changes they might expect in the upcoming releases.
- Simplification release, rename ``Unreleased`` section and add new ``Unreleased``.