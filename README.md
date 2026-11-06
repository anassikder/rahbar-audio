# rahbar-audio

The audio that the Rahbar app downloads. Rahbar is a free Islamic lifestyle app for Android, with no ads and nothing to buy
in the APK edition. The app ships without this audio, so the install stays small, and each person downloads what they want
on Profile › Audio downloads. It then plays offline.

The files are attached to the [releases](https://github.com/anassikder/rahbar-audio/releases), not kept in the repository.
The app downloads them from there and checks each one against a SHA-256 stored in the app, so **don't replace a file in a
release**: new audio goes in a new release with a new tag.

| File | What it holds | Size |
|---|---|---|
| `rahbar-audio-quran.zip` | Two complete Quran recitations | 494 MB |
| `rahbar-audio-meaning.zip` | Muhiuddin Khan's Bangla translation read aloud, one file per ayah | 127 MB |
| `rahbar-audio-hadith.zip` | Two readings of an-Nawawi's Forty Hadith | 14 MB |

## Credits and licences

**The `LICENSE` file in this repository does not cover the audio.** The recordings belong to the people named here, under
their own terms. Use them only as those terms allow.

| Audio | Source | Terms |
|---|---|---|
| Quran recitations by Mishary Rashid Alafasy and Abdur-Rahman as-Sudais | [EveryAyah.com](https://everyayah.com) (`Alafasy_64kbps`, `Abdurrahmaan_As-Sudais_64kbps`), joined into one file per surah | [CC BY-NC 2.5 Canada](https://creativecommons.org/licenses/by-nc/2.5/ca/): attribution, **non-commercial only** |
| Bangla translation audio | Muhiuddin Khan's translation, read by a computer voice from [Comprehensive Bangla TTS](https://github.com/mobassir94/comprehensive-bangla-tts) through [sherpa-onnx](https://github.com/k2-fsa/sherpa-onnx), trained on the [IIT Madras Indic TTS](https://www.iitm.ac.in/donlab/indictts/database) recordings | Voice model: MIT / Apache 2.0. Training recordings: IIT Madras's Indic TTS licence, copyright the TTS Consortium. The words remain under the translation publisher's copyright |
| Forty Hadith readings | Saad al-Ghamdi via [IslamHouse.com](https://islamhouse.com/en/videos/354330/); Abu Malik al-Asqalani via [archive.org](https://archive.org/details/40Hadith_Nawawi) | Freely distributed da'wah material with no stated licence |

If you hold rights in any of this and want it credited differently or removed, please open an issue.
