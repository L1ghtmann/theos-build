# theos-build

GitHub action to build a package with theos

## Usage

```yaml
steps:
    - name: Build Package
      uses: L1ghtmann/theos-build@main
```
OR
```yaml
steps:
    - name: Build Package
      uses: L1ghtmann/theos-build@main
      with:
        extra_args: <space-separated list of args here (e.g., messages=yes, THEOS_DEVICE_IP, etc)>
```

