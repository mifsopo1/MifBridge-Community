<div align="center">

# MifBridge

**Typed, verified automation for Unreal Engine and Blender — driven by an AI agent, read back from the editor.**

[Website](https://mifshowcase.store) · [Documentation](https://mifshowcase.store/docs) · [API reference](https://mifshowcase.store/api-reference) · [Engine support](https://mifshowcase.store/engines) · [Changelog](https://mifshowcase.store/changelog)

</div>

---

MifBridge is a Model Context Protocol (MCP) server fronting two backends:

- **MifBridge** — an in-editor Unreal Engine plugin. Build, wire and compile Blueprint graphs, work with
  assets, levels, materials and sequences, and get the engine's own answer back — compiler errors mapped
  to node and pin, not a screenshot.
- **MifBlender** — a Blender addon. Model, UV-unwrap, rig, light, animate, author geometry nodes and
  render, as typed and guarded operations rather than arbitrary Python.

Every write is read back from the editor before it reports success, and a write that did not happen is
reported as one.

## About this repository

**The MifBridge source is private.** This repository is its public front door: it exists so the links
above have a home, and so you can report a bug.

MifBridge is distributed through Epic's **Fab** marketplace. Current figures — supported engine
versions, endpoint and operation counts — are published on the [website](https://mifshowcase.store),
which reads them from the source rather than from a hand-kept copy.

## Reporting a bug

[Open an issue](../../issues/new/choose) using the bug report template. The most useful reports say:

1. which endpoint (Unreal) or op (Blender) you called, and with what parameters;
2. which engine or Blender version;
3. what came back, and what you expected instead.

A crash log or editor output helps a great deal.

## Licence

MifBridge is proprietary software. See [LICENSE](LICENSE). This repository contains documentation only;
it does not grant any right to the software itself.
