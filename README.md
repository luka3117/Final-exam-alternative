
# 期末代替問題について

この期末テスト代替課題の主な目的は、
授業中に説明したプログラミング言語を理解するために必要な基礎知識を十分に理解しているかを評価するための目的もありますが、同様の重みでこの学期の内容を受講生自ら振り返りながら整理し、自分の知識として定着させる目的が大きいです。

# 問題
以下のテーマから3つ以上の概念を含む報告書を講義中の説明と教科書を参考にまとめて提出してください。

ネット検索や他の文献を参考しても構いませんが、引用元を明記してください。

報告書の分量や形式は自由ですが、各テーマに関するPythonコードのサンプル、その実行結果、結果の解説が含まれるように作成してください。
また、複数のテーマを同時に使ったサンプルコードを解説しても問題ありません。

## テーマ　一覧

1. listとdictionaryについて
    - 例：index方法など
    
2. for文とif文について
    - 例：forとrange関数の組み合わせなど 

3. 関数について
    - 例：簡単な関数を取り上げて解説など
    
4. クラスについて
   - [例えば、講義中解説したこの視聴した後、内容をまとめて報告→動画はこちらをclick](https://youtu.be/ZDa-Z5JzLYM?si=JDdhoCgTlqcFLI8i)

5. (optional)リスト内包表記について
    - 教科書には説明されてない内容
    
      - [参考1](https://realpython.com/list-comprehension-python/#using-for-loops)
      - [参考２](https://realpython.com/list-comprehension-python/#using-list-comprehensionsを読みlistcomprehension)
      
      - hint : 以下の２のコードは同じ結果が返される。list comprehensionを使ったコード(上のコード)はfor分より(下のコード)簡単にコート作成が可能

```
squares = [i * i for i in range(10)]
print(squares)
```
```
sqaures=[]
for i in range(10):
    squares.append(i**2)
    print(squares)
print(squares)
```
