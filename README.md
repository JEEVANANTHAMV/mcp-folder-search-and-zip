# Folder Search & Zip

> Recursively search a folder for files matching a keyword in name or content, and zip folders into a single archive.

The bundle zip (**29.6 MB**) is stored in this repository at **`92fa3c63-3710-4282-ad95-7dc3a7540309.zip`**.

This repository is part of the **Forjinn-Desk** MCP bundle collection. An MCP bundle is a self-contained server that a host application launches and communicates with over the MCP (Model Context Protocol) protocol.

## Repo metadata

| Field | Value |
| --- | --- |
| Registry ID | `92fa3c63-3710-4282-ad95-7dc3a7540309` |
| Status in registry | inactive |
| Bundle size | 29.6 MB |
| Distribution | committed to this repo |

## Environment variables

| Variable | Value / note |
| --- | --- |
| _(none)_ | _no required environment variables_ |

## MCP launch configuration

The host replaces `__INSTALL_DIR__` (install dir) and `__PYTHON__` (bundled Python) at runtime.

```json
{
  "command": "__PYTHON__",
  "args": [
    "server.py"
  ]
}
```

## Setup / usage notes

No special setup required. Ensure the folder you want to search or zip is accessible from your desktop.


## Install / usage

1. Get the bundle:
   - download `92fa3c63-3710-4282-ad95-7dc3a7540309.zip` from this repo (Code → Download ZIP, or `git clone`).
2. Extract to your target installation directory (config paths expect contents at the install-dir root).
3. Set the environment variables listed above.
4. Launch using the MCP config JSON (or let a host client manage it automatically).

> Bundles may include vendored runtimes (bundled Python, Node, or native executables). Builds are Windows x64.
