# Peripheral.Mode

Updated JavaScript codebase for the Alexandria Pedestrian Soundwalk.

This repo contains the modified JS files (route, zones, mic handling) separate from the main PeripheralMode deployment repo.

## Changes from PeripheralMode
- New route: Museum start → El Horeya → Safeya Zaghloul → Seafront → El Naby Danial → side streets → museum end
- One-way zone ratchet (zones only go forward)
- Mic permission deferred to zone 32 with tap button
- True crossfade support (Pd patch change handled separately)