# global-issues

## Front-end issues
### IPFS node issue in browser
- Problem: Webcrypto/SSL cryptography utilities cannot be found
- Solution: Must use HTTPS
- `Uncaught TypeError: Cannot read property 'generateKey' of undefined`
- https://github.com/ipfs/js-ipfs/issues/963
- https://github.com/ipfs/js-ipfs/issues/964
- https://github.com/libp2p/js-libp2p-crypto/issues/105
