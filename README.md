# Branch-Practice

This is practice Repo to test out branching and it's stratages

## Installation


```bash
sudo apt update && sudo apt install python3-full -y 
```
## Usage

### fizzbuzz.py
```python
for i in range(16, 30+1):
# Fizzbuzz 구현 in main
    if i % 15 == 0:
        print('fizzbuzz')
    elif i % 3 == 0:
        print('fizz')
    elif i % 5 == 0:
        print('buzz')
    else:
        print(i)
```
### fivo.py
```
def fibo(n):
    if n < 2:
        return n
    return fibo(n - 1) + fibo(n - 2)

if __name__ == '__main__':
    fibo(7)
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
