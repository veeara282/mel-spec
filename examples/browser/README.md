### WASM Mel Spectrogram with Voice Activity Detection

In this example, a mel WASM worker and AudioWorklets process audio in the
background. They share mel-spectrogram frames with the main UI thread through a
SharedArrayBuffer.

It renders in real-time on an M2 Air.

```sh
npm ci
npm start
```

Run the ring-buffer tests with:

```sh
npm test
```
