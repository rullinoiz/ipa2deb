# ipa2deb
converts ipa to deb in the terminal


# Setup
move downloaded binary to `/usr/local/bin` or run `mv -f ~/Downloads/ipa2deb /usr/local/bin/`
## Parameters
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
