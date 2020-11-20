# Common repository structure
## manifests/
Folder with library manifests. Manifest commonly have this code:
```bash
libName="@creator/library"
libDesc="Example library"
libVer="0.1.2"
libPath="libraries/example/example-0.1.2"
```
But, you can use all shlib variable set and power in this manifest.
This manifest is default shell script, sourced on library list creating.

Common `manifests/` structure is:
```
manifests/:
example  example2  example3
```

## libraries/
Folder with libraries. Common structure is:
```
libraries/:
    example/:
        example
    example2/:
        example2
    example3/:
        example3
```

# WIP

Now this repository is empty. Development is going not very fast, and I'll release first stable enough shlib version.
