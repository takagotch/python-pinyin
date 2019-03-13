### python-pinyin
---
https://github.com/mozillazg/python-pinyin

```py
from pypinyin import pinyin, lazy_pinyin, Style
pinyin('xx')
pinyin('xx', heteronym=True)
pinyin('xx', style=Style.TONE2, heteronym=True)
pinyin('xx', style=Style.BOPOMOFO)
pinyin('xx', style=Style.CYRILLIC)
lazy_pinyin('xx')

from pypinin import Style, pinyin, load_phrase_dic
pinyin('xxxx')
load_phrases_dict({'xx': [['xx'], ['xx'], ['xx'], ['xx']]]})
pinyin('xx')

from pypinyin import Sytle, pinyin
pinyin('xxx', style=Style.INITIALS)

from pypinyin import Style, pinyin
pinyin('xx', style=Style.INITIALS)
pinyin('xx', style=Style.INITIALS, strict=False)
```

```
pip install pypinyin

pypinyin xx
pypinyin -h
```

```
```


