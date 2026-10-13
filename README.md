# PathGuard

Analyze archive-style or user-supplied paths for traversal, absolute-path, reserved-name, and normalization risks.

Version: **1.0.0**

## Installation

```bash
git clone https://github.com/bafnayeygian/PathGuard.git
cd PathGuard
python -m pip install .
```

## Quick start

```bash
path-guard --help
```

Useful when reviewing upload paths, extraction targets, generated filenames, and path normalization.

```bash
path-guard "../secret.txt" "docs/readme.md"
```

## Development

```bash
python -m unittest discover -s tests -v
python -m compileall -q src
```

## License

MIT License.
