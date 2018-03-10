

### SUPPORT

`python 2.7.x`

### TEST
```
python -m tests.tests
```

### Usage
```
from kclient import Article, Groups
article = Article(
            username = '5bc26d24-28c8-446d-a7ae-610dc76fb5a4',
            token = 'e906fd45-a7ac-41e3-a99c-ecd84141f2d3',
            version = '1.3.0')
article.allhistory(Groups.KEYAKIZAKA, 1)
```