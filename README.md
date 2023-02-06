NIP05-VERIF
===========

This repository is for hosting nostr.json, which is used for [NIP-05](https://github.com/nostr-protocol/nips/blob/master/05.md) verification, using Github Pages.

このリポジトリはNostrの[NIP-05](https://github.com/nostr-protocol/nips/blob/master/05.md)に必要な nostr.json ファイルをGithub Pagesでホスティングするためのものです。

Usage
-----

1. Fork this repository.
2. Open index.html, and replace "YOUR_NAME" and "YOUR_PUBKEY" with your own.
3. Convert your PUBKEY to HEX format(=YOUR_PUBKEY_HEX), using [Key Converter](https://damus.io/key/).
4. Open ./well-known/nostr.json and replace <YOUR_NAME> and <YOUR_PUBKEY_HEX> with your own.
5. Deploy!