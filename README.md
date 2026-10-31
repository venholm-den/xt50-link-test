# X-T50 Link Test

A read-only Web Bluetooth page that checks whether a phone can connect to a Fujifilm X-T50 and list its pairing services. It reads only the camera name and firmware and never writes to the camera.

On iPhone, open the GitHub Pages link in the free Bluefy browser (Safari has no Web Bluetooth). On Android, use Chrome.

The registration sequence follows [libfuji](https://github.com/petabyt/libfuji) (MIT) and [furble](https://github.com/gkoh/furble) (`FujifilmBasic`). Only UUIDs and the order of steps are used. No code is copied.
