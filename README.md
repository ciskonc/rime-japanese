# rime-japanese
# 基于个人习惯修改后的版本 主要 修改了 cho 到 kyo  chi 到 ci ji 到 字，还有按照个人习惯添加了一些快捷键
## About

This is a layout for typing in Japanese 日本語. Supports words in all 3 scripts (Kanji, Hiragana, Katakana).


## Installing

First ensure you have plum installed. For macOS this would be:

```bash
cd ~/Library/Rime
wget https://git.io/rime-install
```

Then install `gkovacs/rime-japanese` using plum:

```bash
bash rime-install gkovacs/rime-japanese
```

Finally edit `default.custom.yaml` and add `japanese` to the schema list:

```bash
patch:
  schema_list:
    - schema: japanese
```

Now reload RIME and it should appear under your layouts.
