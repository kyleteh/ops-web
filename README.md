# Ops (web)

A single static page (`index.html`) for SAM Novena Ops, served by GitHub Pages at
https://kyleteh.github.io/ops-web/.

- The page itself contains no data. It reads and writes through the Ops server, which
  needs two things on each device: the **Ops link** and the **access key**.
- Both are typed once per device and kept only in that browser's local storage.
  Neither is stored in this repository.
- Without the link and a valid key the page shows nothing but the setup bar.
- "Clear saved API" / "Forget key on this device" in the top bar remove them from a device.

Built from a private source repository; this repo only receives the assembled page.
