# DBI Patcher v5
Full Translation Patcher for DBI 870–912+.

## Snapshots
<p align="center">
  <img src="https://i.imgur.com/DnUfqZH.jpeg" width="48%" />
  <img src="https://i.imgur.com/I6pGio6.jpeg" width="48%" />
</p>
<p align="center">
  <img src="https://i.imgur.com/MsGQngN.jpeg" width="48%" />
  <img src="https://i.imgur.com/avmTE0S.png" width="48%" />
</p>
<br>

## MINGW64
```bash
pacman -S --needed \
  mingw-w64-x86_64-python \
  mingw-w64-x86_64-python-pip \
  mingw-w64-x86_64-python-keystone \
  mingw-w64-x86_64-python-pillow \
  mingw-w64-x86_64-python-zstandard
```

## Blueprint
```bash
python tools/make_blueprint.py
```

## Translate
```bash
./build.sh
```

## Output
```text
dist/dbi_<language>.zip
```
