# Curmudgeon dictionaries

Word lists that [Curmudgeon Keyboard](https://github.com/curmudgeon-works/curmudgeon-keyboard) downloads on demand,
for languages whose dictionary isn't built into the app. Each file is an Android (AOSP) `.dict` that also works in
HeliBoard and other AOSP-based keyboards: open the downloaded file with the keyboard, or add it from the keyboard's
language settings.

Download page: https://curmudgeon.works/dictionaries

The files are attached to this repository's [Releases](https://github.com/curmudgeon-works/curmudgeon-dictionaries/releases);
`SHA256SUMS` in each release lists their checksums. The links below always point to the latest release.

| Language | Tag | File | Size | Words | Next words | Licence | Attribution |
|---|---|---|---|---|---|---|---|
| Arabic | `ar` | [main_ar.dict](https://github.com/curmudgeon-works/curmudgeon-dictionaries/releases/latest/download/main_ar.dict) | 4.9 MB | 470,783 | yes | CC BY 4.0 | [note](sources/main_ar.source) |
| Catalan | `ca` | [main_ca.dict](https://github.com/curmudgeon-works/curmudgeon-dictionaries/releases/latest/download/main_ca.dict) | 1.9 MB | 239,857 | yes | CC BY 4.0 | [note](sources/main_ca.source) |
| Croatian | `hr` | [main_hr.dict](https://github.com/curmudgeon-works/curmudgeon-dictionaries/releases/latest/download/main_hr.dict) | 5.8 MB | 1,090,327 | yes | CC BY 4.0 | [note](sources/main_hr.source) |
| Czech | `cs` | [main_cs.dict](https://github.com/curmudgeon-works/curmudgeon-dictionaries/releases/latest/download/main_cs.dict) | 16.5 MB | 3,154,785 | yes | CC BY 4.0 | [note](sources/main_cs.source) |
| Danish | `da` | [main_da.dict](https://github.com/curmudgeon-works/curmudgeon-dictionaries/releases/latest/download/main_da.dict) | 9.4 MB | 1,383,621 | yes | CC BY 4.0 | [note](sources/main_da.source) |
| English (Canada) | `en-CA` | [main_en-CA.dict](https://github.com/curmudgeon-works/curmudgeon-dictionaries/releases/latest/download/main_en-CA.dict) | 1.6 MB | 178,863 | yes | CC BY 4.0 | [note](sources/main_en-CA.source) |
| Estonian | `et` | [main_et.dict](https://github.com/curmudgeon-works/curmudgeon-dictionaries/releases/latest/download/main_et.dict) | 5.5 MB | 724,326 | yes | CC BY 4.0 | [note](sources/main_et.source) |
| Finnish | `fi` | [main_fi.dict](https://github.com/curmudgeon-works/curmudgeon-dictionaries/releases/latest/download/main_fi.dict) | 2.8 MB | 322,759 | yes | CC BY 4.0 | [note](sources/main_fi.source) |
| Hindi | `hi` | [main_hi.dict](https://github.com/curmudgeon-works/curmudgeon-dictionaries/releases/latest/download/main_hi.dict) | 2.3 MB | 127,616 | yes | CC BY 4.0 | [note](sources/main_hi.source) |
| Indonesian | `id` | [main_id.dict](https://github.com/curmudgeon-works/curmudgeon-dictionaries/releases/latest/download/main_id.dict) | 1.7 MB | 229,483 | yes | CC BY 4.0 | [note](sources/main_id.source) |
| Latvian | `lv` | [main_lv.dict](https://github.com/curmudgeon-works/curmudgeon-dictionaries/releases/latest/download/main_lv.dict) | 2.7 MB | 346,715 | yes | CC BY 4.0 | [note](sources/main_lv.source) |
| Lithuanian | `lt` | [main_lt.dict](https://github.com/curmudgeon-works/curmudgeon-dictionaries/releases/latest/download/main_lt.dict) | 3.3 MB | 442,554 | yes | CC BY 4.0 | [note](sources/main_lt.source) |
| Norwegian Bokmål | `nb` | [main_nb.dict](https://github.com/curmudgeon-works/curmudgeon-dictionaries/releases/latest/download/main_nb.dict) | 7.6 MB | 1,133,014 | yes | CC BY 4.0 | [note](sources/main_nb.source) |
| Persian | `fa` | [main_fa.dict](https://github.com/curmudgeon-works/curmudgeon-dictionaries/releases/latest/download/main_fa.dict) | 12.7 MB | 1,520,799 | yes | CC BY 4.0 | [note](sources/main_fa.source) |
| Slovenian | `sl` | [main_sl.dict](https://github.com/curmudgeon-works/curmudgeon-dictionaries/releases/latest/download/main_sl.dict) | 6.0 MB | 1,184,096 | yes | CC BY 4.0 | [note](sources/main_sl.source) |
| Thai | `th` | [main_th.dict](https://github.com/curmudgeon-works/curmudgeon-dictionaries/releases/latest/download/main_th.dict) | 1.1 MB | 87,336 | no | CC0 1.0 | [note](sources/main_th.source) |
| Ukrainian | `uk` | [main_uk.dict](https://github.com/curmudgeon-works/curmudgeon-dictionaries/releases/latest/download/main_uk.dict) | 12.7 MB | 1,347,649 | yes | CC BY 4.0 | [note](sources/main_uk.source) |

## Licences and attribution

Every file has a source note in [`sources/`](sources/) (also attached to the release) naming where its words come from
and under which licence. In short:

- **Hindi** was built by Curmudgeon Works from the [Leipzig Corpora Collection](https://wortschatz.uni-leipzig.de/en/download/)
  Hindi corpora (CC BY 4.0). The list is under CC BY 4.0.
- **Thai** comes from [Helium314/aosp-dictionaries](https://codeberg.org/Helium314/aosp-dictionaries), built from the
  [PyThaiNLP](https://github.com/PyThaiNLP/pythainlp) corpus word list (CC0 1.0).
- **All other languages** come from Helium314/aosp-dictionaries, built from the Leipzig Corpora Collection
  (CC BY 4.0). Those lists are under CC BY 4.0.

Leipzig Corpora Collection: D. Goldhahn, T. Eckart, U. Quasthoff: *Building Large Monolingual Dictionaries at the
Leipzig Corpora Collection: From 100 to 200 Languages.* LREC 2012.

`dictionaries.json` is the machine-readable list (tag, file, size, words, licence, SHA-256).

Questions: hello@curmudgeon.works
