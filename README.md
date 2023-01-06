## Reference

- [SUUMOの物件情報を自動取得（スクレイピング）したのでコードを解説する。 \- Qiita](https://qiita.com/tomyu/items/a08d3180b7cbe63667c9)

## Python Version

- ^3.11

## Settings

put your settings in `settings.py`. Only two variables are required!

```python
Base_URL = "https://suumo.jp/jj/chintai/ichiran/~"
Max_Pages = 5
```

## Usage

Choose one of [Poetry](https://python-poetry.org/) or [pip](https://pip.pypa.io/en/stable/) to install the required packages. Poetry is recommended.

### Using Poetry

```bash
$ poetry install
$ poetry shell
$ python suu.py
```

or

```bash
$ poetry install
$ poetry run python suu.py
```

### Using pip

```bash
$ pip install -r requirements.txt
$ python suu.py
```

## Background process option

```bash
$ nohup python suu.py &
```
