# CHANGELOG


## v1.0.0 (2026-04-02)

### Bug Fixes

- Bump minimum Python version to 3.9 for filelock compatibility
  ([#19](https://github.com/jamesharding/PlexMusicRatingsSync/pull/19),
  [`a9fca7c`](https://github.com/jamesharding/PlexMusicRatingsSync/commit/a9fca7ce74433a2988e2651326f2b96367688196))

filelock 3.17.0 requires Python >=3.9

- Handle missing track index numbers in Plex library
  ([#4](https://github.com/jamesharding/PlexMusicRatingsSync/pull/4),
  [`2e6df6a`](https://github.com/jamesharding/PlexMusicRatingsSync/commit/2e6df6adef0993e84ffa2811cb77996156135a45))

- Handle OGG files with non-Vorbis codecs failing to sync
  ([#23](https://github.com/jamesharding/PlexMusicRatingsSync/pull/23),
  [`fb6551d`](https://github.com/jamesharding/PlexMusicRatingsSync/commit/fb6551d8c37170ada83af09cf954069aa94d8504))

- Implement Windows-compatible single instance lock mechanism
  ([`fb9b204`](https://github.com/jamesharding/PlexMusicRatingsSync/commit/fb9b204758af97c5e93f2c14b1f56ae6bec18f35))

- Remove logs that were meant for debugging only
  ([`b40faec`](https://github.com/jamesharding/PlexMusicRatingsSync/commit/b40faecef49a5cc8d4657482369ff53d84fa12fe))

### Chores

- Add `.gitignore` with common Python patterns
  ([`1bea1c9`](https://github.com/jamesharding/PlexMusicRatingsSync/commit/1bea1c927f716282d9f962d05b27a6d61e45f5aa))

- Add `.venv/` to `.gitignore`
  ([`a98aea8`](https://github.com/jamesharding/PlexMusicRatingsSync/commit/a98aea8c61bc9d63adcc9f539ca7c235b1212675))

- **deps**: Bump Python to 3.9 ([#19](https://github.com/jamesharding/PlexMusicRatingsSync/pull/19),
  [`a9fca7c`](https://github.com/jamesharding/PlexMusicRatingsSync/commit/a9fca7ce74433a2988e2651326f2b96367688196))

### Continuous Integration

- Do not run unnecessary steps if no release was made
  ([`01903de`](https://github.com/jamesharding/PlexMusicRatingsSync/commit/01903de1f3295c29564fb19d6a7a9f8bd7b315df))

### Documentation

- Add feature to `README.md` erroneously removed
  ([`ea969ad`](https://github.com/jamesharding/PlexMusicRatingsSync/commit/ea969ad0600f7ea2027ef90ada7acdd7300f1002))

- Add funding options for Ko-fi and Buy Me a Coffee
  ([`b67795b`](https://github.com/jamesharding/PlexMusicRatingsSync/commit/b67795b3e23e1e277e8f5e097e76d0f034a8bb40))

- Add GitHub funding information
  ([`7265ee6`](https://github.com/jamesharding/PlexMusicRatingsSync/commit/7265ee670d227d4133dbd6c3b3b981d6b1761657))

- Remove duplicate changelog entries
  ([`f713ad0`](https://github.com/jamesharding/PlexMusicRatingsSync/commit/f713ad09cedd5dc1960a4f5ebce1b323edb81973))

### Features

- Add AIFF support ([#15](https://github.com/jamesharding/PlexMusicRatingsSync/pull/15),
  [`6cf6ccc`](https://github.com/jamesharding/PlexMusicRatingsSync/commit/6cf6ccce57114046160f60fde1b54808e7f94dd8))

- Add environment variable overrides for plex config values
  ([#25](https://github.com/jamesharding/PlexMusicRatingsSync/pull/25),
  [`a39b6aa`](https://github.com/jamesharding/PlexMusicRatingsSync/commit/a39b6aaaddb4c8bc61fe1e3a69e305cf8333b434))

- Add mtime-based file rating cache and processing summary
  ([#24](https://github.com/jamesharding/PlexMusicRatingsSync/pull/24),
  [`ef59466`](https://github.com/jamesharding/PlexMusicRatingsSync/commit/ef5946691b35b0fda9f328e8ededc6498b0fd1bb))

- Add mtime-based file rating cache to skip unchanged files
  ([#24](https://github.com/jamesharding/PlexMusicRatingsSync/pull/24),
  [`ef59466`](https://github.com/jamesharding/PlexMusicRatingsSync/commit/ef5946691b35b0fda9f328e8ededc6498b0fd1bb))

- Add processing summary with cache, update, and skip stats
  ([#24](https://github.com/jamesharding/PlexMusicRatingsSync/pull/24),
  [`ef59466`](https://github.com/jamesharding/PlexMusicRatingsSync/commit/ef5946691b35b0fda9f328e8ededc6498b0fd1bb))

- Add support for `.m4a` (AAC/ALAC) file formats
  ([`c508263`](https://github.com/jamesharding/PlexMusicRatingsSync/commit/c508263541f5e90532440c27002e09509bb0fc29))

- Add support for `.ogg` and `.opus` file formats
  ([`b99e928`](https://github.com/jamesharding/PlexMusicRatingsSync/commit/b99e92813a497732d30cf9cf8c4d17c605b4b608))

- Initial version
  ([`f623ff5`](https://github.com/jamesharding/PlexMusicRatingsSync/commit/f623ff52b2d89e91b001420ac8eec06ad3f960c6))

### Refactoring

- Remove redundant `Path` conversion from `logger`
  ([`254b4d0`](https://github.com/jamesharding/PlexMusicRatingsSync/commit/254b4d022889bf097002b8c03c1b36ac66f591bf))
