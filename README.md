# my-scoop-bucket
This is a repository for my own scoop bucket.

## bucket add

```
scoop bucket add openjny https://github.com/OpenJNY/my-scoop-bucket.git
```

## dev

### calculate checksum

```powershell
> CertUtil -hashfile foobar.zip SHA256
```

### autoupdate

[App Manifest Autoupdate · lukesampson/scoop Wiki](https://github.com/lukesampson/scoop/wiki/App-Manifest-Autoupdate)

```powershell
> ~\scoop\apps\scoop\current\bin\checkver.ps1 -Dir .\bucket
```