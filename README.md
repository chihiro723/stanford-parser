# stanford-parser
## 1. 名詞カテゴリー (Nouns)
| タグ | 名称 | 説明 | 例 |
|------|------|------|-----|
| NN | 普通名詞（単数） | 数えられる一般的な物事の名称 | book, desk |
| NNS | 普通名詞（複数） | 普通名詞の複数形 | books, desks |
| NNP | 固有名詞（単数） | 特定の人、場所、組織等の名称 | John, Tokyo |
| NNPS | 固有名詞（複数） | 固有名詞の複数形 | Americans, Alps |

## 2. 代名詞カテゴリー (Pronouns)
| タグ | 名称 | 説明 | 例 |
|------|------|------|-----|
| PRP | 人称代名詞 | 人や物を指す代名詞 | I, you, he, she, it |
| PRP$ | 所有代名詞 | 所有を表す代名詞 | my, your, his, her |
| WP | Wh代名詞 | 疑問文や関係詞で使用 | who, what, which |
| WP$ | 所有格Wh代名詞 | 所有を表すWh代名詞 | whose |
| EX | 存在を表す "there" | 存在文で使用される特殊な代名詞 | there (There is...) |

## 3. 動詞カテゴリー (Verbs)
| タグ | 名称 | 説明 | 例 |
|------|------|------|-----|
| VB | 動詞（原形） | 動詞の基本形 | write, read |
| VBD | 動詞（過去形） | 過去を表す動詞 | wrote, read |
| VBG | 動詞（現在分詞） | -ing形の動詞 | writing, reading |
| VBN | 動詞（過去分詞） | 受動態や完了形で使用 | written, read |
| VBP | 動詞（現在形） | 三人称単数以外の現在形 | write, read |
| VBZ | 動詞（三人称単数現在） | 三人称単数の現在形 | writes, reads |
| MD | 助動詞 | 可能性や義務を表す補助動詞 | can, must, should |

## 4. 形容詞カテゴリー (Adjectives)
| タグ | 名称 | 説明 | 例 |
|------|------|------|-----|
| JJ | 形容詞 | 物事の性質を表す語 | happy, tall |
| JJR | 形容詞（比較級） | 比較を表す形容詞 | happier, taller |
| JJS | 形容詞（最上級） | 最上を表す形容詞 | happiest, tallest |

## 5. 副詞カテゴリー (Adverbs)
| タグ | 名称 | 説明 | 例 |
|------|------|------|-----|
| RB | 副詞 | 動詞、形容詞を修飾する語 | quickly, well |
| RBR | 副詞（比較級） | 比較を表す副詞 | faster, better |
| RBS | 副詞（最上級） | 最上を表す副詞 | fastest, best |
| WRB | Wh副詞 | 疑問副詞 | when, where, why |

## 6. 前置詞と接続詞カテゴリー (Prepositions and Conjunctions)
| タグ | 名称 | 説明 | 例 |
|------|------|------|-----|
| IN | 前置詞/従属接続詞 | 場所や関係を示す語 | in, of, because |
| CC | 等位接続詞 | 語や句を結ぶ接続詞 | and, or, but |

## 7. 限定詞と冠詞カテゴリー (Determiners and Articles)
| タグ | 名称 | 説明 | 例 |
|------|------|------|-----|
| DT | 限定詞 | 名詞の前に置かれる語 | the, a, an, this |
| PDT | 前限定詞 | 限定詞の前に置かれる語 | all, both |
| WDT | Wh限定詞 | 疑問限定詞 | which, what |

## 8. その他の品詞 (Others)
| タグ | 名称 | 説明 | 例 |
|------|------|------|-----|
| CD | 基数 | 数を表す語 | one, two, 1, 2 |
| RP | 助詞 | 句動詞の一部 | up (in "look up") |
| SYM | 記号 | 数学記号や通貨記号など | +, $, % |
| TO | to | 不定詞を作る"to" | to |
| UH | 間投詞 | 感嘆や驚きを表す語 | oh, wow |
| LS | リストマーカー | 箇条書きの記号 | 1., A., (1) |
| FW | 外国語 | 英語以外の言葉 | rendez-vous |
| POS | 所有格マーカー | 所有を表す's | John's |

## 9. 句構造タグ (Phrase Level)
| タグ | 名称 | 説明 | 例 |
|------|------|------|-----|
| NP | 名詞句 | 名詞とその修飾語を含む句 | the red book |
| VP | 動詞句 | 動詞とその補語を含む句 | is reading a book |
| PP | 前置詞句 | 前置詞と名詞句を含む句 | in the room |
| ADJP | 形容詞句 | 形容詞とその修飾語を含む句 | very happy |
| ADVP | 副詞句 | 副詞とその修飾語を含む句 | quite slowly |
| SBAR | 従属節 | 従属接続詞で始まる節 | that he came |

## 10. 文レベルのタグ (Clause Level)
| タグ | 名称 | 説明 | 例 |
|------|------|------|-----|
| S | 文 | 完全な文を表す | He reads books |
| SINV | 倒置文 | 主語と動詞が倒置した文 | Never have I seen |
| SQ | 疑問文 | Yes/No疑問文や疑問詞疑問文 | Did he come? |
| SBARQ | Wh疑問文 | Wh疑問詞を含む疑問文 | What did he say? |
| FRAG | 断片 | 完全な文ではない断片 | Me too! |

## 11. 特殊タグ (Special Tags)
| タグ | 名称 | 説明 | 例 |
|------|------|------|-----|
| ROOT | ルート | 解析木の最上位ノード | 文全体 |
| X | 不明または分類不能 | 通常の品詞分類に当てはまらない要素 | - |
| INTJ | 間投句 | 感嘆や驚きを表す句 | Oh my god! |
| PRN | 括弧内の表現 | 括弧で囲まれた補足的な表現 | (I think) |

## 12. 句読点 (Punctuation)
| タグ | 名称 | 説明 | 例 |
|------|------|------|-----|
| . | ピリオド | 文末のピリオド | . |
| , | カンマ | 句読点のカンマ | , |
| : | コロン | コロン | : |
| -LRB- | 左括弧 | 開き括弧 | ( [ { |
| -RRB- | 右括弧 | 閉じ括弧 | ) ] } |
