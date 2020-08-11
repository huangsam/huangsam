```python
def try_again():
    return random() > 0.99


def main():
    success = False
    while success is not True:
        success = try_again()


if __name__ == '__main__':
    main()
```
