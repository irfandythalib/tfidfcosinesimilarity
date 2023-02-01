# TFIDF dan Cosine Similary Untuk Document Search Enginee Bahasa Indonesia
Di sini, kita melihat bagaimana menggunakan TFIDF dan Cosine Similarity untuk mencari dokumen terkait dari dataset dari kueri yang diinputkan. Di contoh ini kita menggunakan dokumen bahasa Indonesia. Walaupun sebenarnya kode ini bukannya Language dependent, artinya bisa digunakan untuk bahasa apapun.

#### Library
Library yang digunakan adalah pandas dan SKlearn. Cukup memanggilnya dengan cara berikut.
```
from sklearn.feature_extraction.text import TfidfVectorizer
import pandas as pd
```
