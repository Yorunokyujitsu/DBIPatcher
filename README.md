# DBI Translation Archive
An archive of DBI builds translated using DBIPatcher v5.

Full translations for DBI 870–912+ (26 versions included).
- DBI 814–912 is compatible, but the range is limited to 870–912 for easier translation string management.
- Translated 1,387 strings and 147 version-specific strings.
- Added Easter egg menu visualization and translation patches.
- Added language-specific version display patches.
  - **Example: DBI: 912-KR FW: 23.0.1.E SDK: 23.3.0**

> [!CAUTION]
> **Author Controversy:**<br>
> **This translation is not affiliated with the original DBI author.**<br>
> **Please be aware of the controversy surrounding the author.**<br>
> **Any use of DBI is solely the user's responsibility.**<br>

<br>

## Snapshots
<p align="center">
  <img src="https://i.imgur.com/DnUfqZH.jpeg" width="48%" />
  <img src="https://i.imgur.com/I6pGio6.jpeg" width="48%" />
</p>
<p align="center">
  <img src="https://i.imgur.com/MsGQngN.jpeg" width="48%" />
  <img src="https://i.imgur.com/WWP9eWc.jpeg" width="48%" />
</p>
<p align="center">
  <img src="https://i.imgur.com/axLpWs2.jpeg" width="48%" />
  <img src="https://i.imgur.com/avmTE0S.png" width="48%" />
</p>
<br>

## Prerequisites
```bash
python -m pip install keystone-engine zstandard Pillow
```

## Blueprint
```bash
python tools/make_blueprint.py
```

## Translate
```bash
python tools/make_translate.py
```

## Patch
```bash
lock=0 patch=1 ver=912 bash build.sh
```

## Output
```text
dist/dbi_<language>.zip
```
<br>

## Credits
> v1: Morce3232<br>
> v2: Morce3232, bohdan.buinich, Yorunokyujitsu<br>
> v3-v5: Yorunokyujitsu<br>
> Font: Dalgona - neodgm