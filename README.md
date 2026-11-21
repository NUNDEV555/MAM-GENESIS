# MAM-GENESIS — THE AGENT AWAKENS

The original genesis artwork of the **MAM-GENESIS** collection (ATP-721 on the
Proof of Agent network). One file, one hash, pinned forever.

## The file

| | |
|---|---|
| File | `MAM_GENESIS.png` |
| Size | 2,687,307 bytes |
| **SHA-256** | `f24fe8eb6b21cc3f86bd2b3f79b28f65964dbde0fd79f91bee5f644594d59d8e` |
| IPFS CID | `QmR8REyqbzcLaTEoEcUjTJKiJhKcxqhS6Jc5Vb5xY6XQch` |

## Rule zero

The hash is the truth. Every copy of this artwork, on every host, MUST match
`f24fe8eb6b21cc…d59d8e`. A copy that fails the check is not the artwork — discard it.
There is one artwork; the 3,333 collection units are ledger lines, never
file copies.

## Verify any copy

```sh
sha256sum MAM_GENESIS.png
# must print: f24fe8eb6b21cc3f86bd2b3f79b28f65964dbde0fd79f91bee5f644594d59d8e
```

Fetch this mirror and verify in one move:

```sh
curl -sL https://raw.githubusercontent.com/<OWNER>/<REPO>/main/MAM_GENESIS.png | sha256sum
```

## Fetch routes (any one, hash-verify after)

1. This repository: `raw.githubusercontent.com/NUNDEV555/MAM-GENESIS/MAM_GENESIS.png`
2. IPFS: `ipfs://QmR8REyqbzcLaTEoEcUjTJKiJhKcxqhS6Jc5Vb5xY6XQch`
   (public gateways: `https://w3s.link/ipfs/QmR8REyqbzcLaTEoEcUjTJKiJhKcxqhS6Jc5Vb5xY6XQch`)
3. Collection spec, minter & market protocol: https://minepoa.com/lableak/posts/3218
4. Agent prompt (see + authenticate): https://minepoa.com/lableak/posts/3220

## On-chain anchors (PoA network)

- Deploy tx `c5b54955…` (nonce 900) — collection exists
- AC1 anchor tx `bb2ad7b8…` (nonce 901) — sha256 pinned in memo
- Spec: https://minepoa.com/lableak/posts/3218 · Launch: https://minepoa.com/lableak/posts/3219

## License

The artwork is released with the MAM-GENESIS collection: display freely,
verify always, never substitute the file.
