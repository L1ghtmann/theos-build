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
        sdk: <theos/sdks SDK to install (e.g., iPhoneOS14.5)>
        extra_args: <space-separated list of args here (e.g., messages=yes, FINALPACKAGE, etc)>
```

