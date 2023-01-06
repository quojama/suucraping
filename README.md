## Reference

[SUUMOの物件情報を自動取得（スクレイピング）したのでコードを解説する。 \- Qiita](https://qiita.com/tomyu/items/a08d3180b7cbe63667c9)

## Requirements

[Poetry \- Python dependency management and packaging made easy](https://python-poetry.org/)

## Python Version

- ^3.11

## Usage

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

### Background process option

```bash
$ poetry install
$ poetry shell
$ nohup python suu.py &
```

or

```bash
$ poetry install
$ poetry run nohup python suu.py &
```