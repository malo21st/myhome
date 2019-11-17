# Python Boot Camp in 福岡2nd

ＴＡ（講師のアシスタント）をする際に、PythonBootCampテキストを勉強した時の成果物などです。

## Fizz Buzz

!!! Tip
    - FizzBuzzのリスト内包表記での実装
    - [リスト内包表記でFizzBuzz](https://qiita.com/ssh0/items/23629be59af1dd3e7c41)
    
```python
print(*[(i%3==0)*'Fizz' + (i%5==0)*'Buzz' or i for i in range(1, 101)])
```

!!! Tip
    - 辞書を使って実装
    
```python
surplus15 = {0:"FizzBuzz", 3:"Fizz", 5:"Buzz", 6:"Fizz", 9:"Fizz", 10:"Buzz", 12:"Fizz"}

for i in range(1,101):
    print(surplus15.get(i % 15, i), end=" ")
```
