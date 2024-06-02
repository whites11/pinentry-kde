# pinentry-kde

This is a [pinentry](https://github.com/gpg/pinentry/blob/master/README) implementation written in bash with cache support using Kwallet.

Meant to be used via gpg-agent to unlock a smart card using it's pin code.

## Dependencies

- kwallet
- secret-tool
- kdialog

## Credits

Heavily inspired by https://github.com/legionus/pinentry-bash

## Disclaimer

The implementation is partial and will likely not cover all use cases.