### 前缀树

    即字典树（Trie），是一种有序树形结构。它的优点是最大限度地的减少无谓的字符串比较，查询效率比较高。典型应用是用于统计和排序大量的字符串（但不不仅限于字符串）

##### 核心思想
    空间换时间。利用字符串的公共前缀来降低查询时间的开销已达到提高效率的目的。