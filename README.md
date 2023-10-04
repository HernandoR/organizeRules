my rules to use [organize](https://github.com/tfeldmann/organize)

install guide: [organize](https://organize.readthedocs.io/en/latest/#getting-started)

```
conda create -n organize python=3.8 -y
conda activate organize
pip install "organize-tool[texttract]"
```

## Usage

```
organize -c organize.yaml
```
## templates:
```yaml
# rules:
#   # First rule
#   - name: ...
#     enabled: ...
#     targets: ...
#     locations: ...
#     subfolders: ...
#     filter_mode: ...
#     filters: ...
#     actions: ...
#     tags: ...

#   # Another rule
#   - name: ...
#     enabled: ...
#     # ... and so on

```