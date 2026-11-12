# Ops (web)

A single static page (`index.html`) for SAM Novena Ops, served by GitHub Pages at
https://kyleteh.github.io/ops-web/.

- The page itself contains no data. It reads and writes through the Ops server.
- On a new device it asks for one password. The server address is in the page only in
  encrypted form, and the password unlocks it. The password is typed once per device and
  kept in that browser's local storage; it is not stored in this repository.
- The server checks the password on every call and locks a device after repeated wrong tries.
- The small "Device" link at the bottom right can clear the saved address or password on a device.

Built from a private source repository; this repo only receives the assembled page.
