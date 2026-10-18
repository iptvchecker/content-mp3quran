# MP3Quran original resource mirror

Faithful copies of selected original MP3Quran Warsh and Qaloon recordings and
publisher timing responses. Publisher permission: https://www.mp3quran.net/ar/privacy
Original publisher: https://www.mp3quran.net/

Original recording bytes and publisher credit are retained.

Audio is supplied as GitHub release assets, one immutable dated release
per publisher recording ID. Each release retains SOURCE.json and CHECKSUMS.sha256.

Publisher timing JSON lives under timings/READING-ID/2026-10-08/. These are exact
original responses, not app-corrected timing data. Known app-specific corrections
must be reviewed separately at integration; they are not applied to source mirrors.

Source versions, observed HTTP validators, retrieval dates, byte counts and SHA-256
hashes are recorded. Publisher publication dates are not invented when absent;
HTTP Last-Modified is kept as an observed validator, not assumed to be publication.

Later updates go into new dated snapshots and review branches. Never delete older
files or releases automatically because upstream removes or changes its resources.
Existing app-pinned releases must remain available. No app endpoint is changed here.

## Published snapshot — 2026-10-08

All seven recordings below contain 114 unchanged original MP3 files. All 798
MP3s total 11,277,368,909 bytes (11.28 GB); each release asset is below 2 GiB.
An independent post-publication audit matched the sizes and GitHub SHA-256
content digests of all 812 release assets, including provenance/checksum files.
Anonymous range downloads were also checked, including Yassin Yusuf (012).

[Download inventory with per-surah URLs, sizes and SHA-256 hashes](DOWNLOADS.json).

| Narration | Reciter — العربية | Reciter — English | Original MP3s |
| --- | --- | --- | --- |
| qalon | [الدوكالي محمد العالم](https://github.com/iptvchecker/content-mp3quran/releases/tag/qalon-dokali208-2026-10-08) | Addokali Mohammad Alalim | 114 |
| qalon | [علي بن عبدالرحمن الحذيفي](https://github.com/iptvchecker/content-mp3quran/releases/tag/qalon-hudhaify75-2026-10-08) | Ali Alhuthaifi | 114 |
| qalon | [محمود خليل الحصري](https://github.com/iptvchecker/content-mp3quran/releases/tag/qalon-husary270-2026-10-08) | Mahmoud Khalil Al-Hussary | 114 |
| warsh | [محمود خليل الحصري](https://github.com/iptvchecker/content-mp3quran/releases/tag/warsh-husary120-2026-10-08) | Mahmoud Khalil Al-Hussary | 114 |
| warsh | [العيون الكوشي](https://github.com/iptvchecker/content-mp3quran/releases/tag/warsh-koshi16-2026-10-08) | Aloyoon Al-Koshi | 114 |
| warsh | [عمر القزابري](https://github.com/iptvchecker/content-mp3quran/releases/tag/warsh-qazabri80-2026-10-08) | Omar Al-Qazabri | 114 |
| warsh | [القارئ ياسين](https://github.com/iptvchecker/content-mp3quran/releases/tag/warsh-yassin14-2026-10-08) | Al-Qaria Yassen | 114 |

Listing change (October 18, 2026): this README displays Arabic and English reciter names copied from MP3Quran’s Arabic and English API catalogs, matched by the existing recording (moshaf) IDs. This makes the seven existing collections identifiable in both languages. Only this explanatory listing changed; original provider metadata, recordings, timing responses, filenames and download links were not modified. App-specific localization and corrections are maintained separately in the app.

Name sources: [Arabic catalog](https://www.mp3quran.net/api/v3/reciters?language=ar), [English catalog](https://www.mp3quran.net/api/v3/reciters?language=eng).

## Distinct source mirrors

| Publisher mirror | Published scope |
| --- | --- |
| [Quran SVG](https://github.com/iptvchecker/content-quran-svg) | Original repository history and 604 original v1.1.1 word-coordinate sidecars |
| [Tanzil](https://github.com/iptvchecker/content-tanzil) | Original Uthmani 1.1 text and notice |
| [Quranpedia](https://github.com/iptvchecker/content-quranpedia) | Original Asbab book 2919 archive and license |
| [QuranEnc](https://github.com/iptvchecker/content-quranenc) | Six original publisher SQLite ZIPs and 684 unchanged chapter responses |
| [Quran JSON](https://github.com/iptvchecker/content-quran-json) | Original Warsh/Qalun text, mapping and upstream attribution |
| [Al Quran Cloud](https://github.com/iptvchecker/content-alquran-cloud) | Original Pickthall and al-Muyassar responses and edition credits |
| This MP3Quran mirror | Seven complete recordings and 798 unchanged timing responses |

Original timing responses are retained unchanged. Source metadata and checksum
records accompany each mirrored collection.

## Mirror documentation update — October 18, 2026

Simplified the mirror description to focus on content, sources and file layout. Corrected the app name where needed. Original content files, provider metadata, notices, licenses, filenames and checksum records were not changed.
