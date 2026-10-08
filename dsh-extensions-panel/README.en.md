# dsh-extensions-panel

> This branch is the **vk-free build**: official slots only, no vk slot references; identical behaviour with or without dsh-vk-suite. The vk build is on the [main branch](https://github.com/Ln1m/dsh-extensions-panel/tree/main).

> This branch is the **vk-free build** (no vk dependency): it registers the official `sidebar.panellist` slot (left-rail icon) plus the `main` slot (centre panel). The vk build is on the [main branch](https://github.com/Ln1m/dsh-extensions-panel/tree/main) and needs [dsh-vk-suite](https://github.com/Ln1m/dsh-vk-suite).
> Conflicts: a slot renders only its highest-priority entry, and two registrations at the same priority throw; mutually exclusive with anything claiming the same position (see "How to use it / what it conflicts with" in [dsh-vk-suite](https://github.com/Ln1m/dsh-vk-suite)).

[中文](README.md) · English

![Virtual-display card in the Extensions tab](assets/dsh-extensions-panel.png)

*Screenshot of a running DSH instance; demo content is sanitized.*

Registers a virtual-display toggle card inside the vk layout's left-column "Extensions" tab (`vk.sidebar.extensions`).

## Install

```sh
dsh plugin --profile web add file:<this repo>
```

Restart the web instance afterwards.
