# Russian Synodal Bible / Синодальный Перевод

## Source
Downloaded from https://bible.by/download/

Converted from Windows-1251 to UTF-8 using https://github.com/nijel/enca

```bash
for file in [original_source_dir]/*
do
enconv -V -L russian -x UTF-8 $file
done
```
