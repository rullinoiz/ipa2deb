# ipa2deb
converts ipa to deb in the terminal


# Setup
first grab the latest release from the [release page](https://github.com/rullinoiz/ipa2deb/releases)
## macOS (and maybe linux idk)
move downloaded binary to `/usr/local/bin` or run `mv -f ~/Downloads/ipa2deb /usr/local/bin/`
## iOS
install the latest deb file from the [release page](https://github.com/rullinoiz/ipa2deb/releases) or [add my cydia repo](https://repoiz.github.io/repoiz)
## Windows
not yet available, i'll have to rewrite the whole thing
## Actual usage
right now it's only:

```ipa2deb /path/to/ipa /path/to/metadata (optional)```

by the way, it will ask for the metadata and ipa if they are missing in case you forgot to specify them

# Troubleshooting
if anything goes wrong, here are some solutions to problems i have faced
## Access denied
Try:
- running `chmod +x /usr/local/bin/ipa2deb`
- redownloading the file and follow the setup again
## Command not found
Try:
- redoing the setup
- run `zsh`
- run `bash`

(might be your shell not seeing it)
