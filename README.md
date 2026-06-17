# doccaz.github.io

Personal projects portal — a static GitHub Pages site listing all open source tools and projects published at **doccaz.github.io**.

## Live

👉 **[doccaz.github.io](https://doccaz.github.io)**

---

## 🌐 Web Tools (live in the browser)

| Tool | URL | Description |
|---|---|---|
| Cloud-Init Generator | [doccaz.github.io/cloud-init](https://doccaz.github.io/cloud-init) | Visually compose and validate cloud-init configs with real-time YAML output |
| Harvester CloudInit Editor | [doccaz.github.io/harvester-cloud-init](https://doccaz.github.io/harvester-cloud-init) | Visual editor for Harvester & Elemental CloudInit CRDs, with optional AI assistance |
| Harvester Configurator | [doccaz.github.io/harvester-configurator](https://doccaz.github.io/harvester-configurator) | Guided wizard for Harvester v1.7+ automated install YAML |
| NeuVector Visualizer | [doccaz.github.io/neuvector-visualizer](https://doccaz.github.io/neuvector-visualizer) | Interactive HTML5 demo of NeuVector DPI and Zero Trust container security |
| LCD Matrix Studio | [doccaz.github.io/pixel-matrix-studio](https://doccaz.github.io/pixel-matrix-studio) | Bitmap editor for monochrome LCD/OLED displays; exports C PROGMEM arrays |
| SUSE AI Sizing Architect | [doccaz.github.io/suse-ai-sizing-tool](https://doccaz.github.io/suse-ai-sizing-tool/) | Browser-based planning tool for estimating compute, memory, GPU and storage footprint of a SUSE AI deployment |
| MeshPrep | [doccaz.github.io/meshprep](https://doccaz.github.io/meshprep/) | Browser-based OBJ/STL mesh editor and 3D print optimizer for FDM and SLA printing |

---

## 📦 Other Projects

### SUSE

| Repo | Description |
|---|---|
| [scc-tools](https://github.com/doccaz/scc-tools) | CLI tools for SUSE Customer Center: package version lookup, supportconfig analysis, public cloud image tracking |
| [susemanager-api](https://github.com/doccaz/susemanager-api) | Script collection for the SUSE Manager / Uyuni XML-RPC API |
| [scap2salt](https://github.com/doccaz/scap2salt) | Converts SCAP remediation content into SaltStack states |
| [suse-cve-analyzer](https://github.com/doccaz/suse-cve-analyzer) | Correlates CVE data against installed packages on SUSE/openSUSE systems |
| [gsplugin-customcategories](https://github.com/doccaz/gsplugin-customcategories) | GNOME Software plugin that maps non-standard app categories (e.g. X-YaST) to visible store sections |

### Virtualization

| Repo | Description |
|---|---|
| [kvm-scripts](https://github.com/doccaz/kvm-scripts) | Network hook scripts for QEMU/KVM: port forwarding, network restart, QEMU Guest Agent CLI |
| [labvirtual](https://github.com/doccaz/labvirtual) | Flask-based web frontend for QEMU/KVM lab environments with noVNC/SPICE console support |
| [vm-import-ui](https://github.com/doccaz/vm-import-ui) | Container-based web UI for orchestrating VM imports into Harvester HCI |
| [nutanix-exporter](https://github.com/doccaz/nutanix-exporter) | Exports VMs from Nutanix AHV to QCOW2 images with QEMU/Libvirt definitions; includes AHV CE install guide |

### Kubernetes & Containers

| Repo | Description |
|---|---|
| [nfs-server-bci](https://github.com/doccaz/nfs-server-bci) | Containerized NFS server on SUSE BCI for Kubernetes persistent storage |
| [eks-demos](https://github.com/doccaz/eks-demos) | Demo scripts and manifests for Amazon EKS |

### Security

| Repo | Description |
|---|---|
| [update-browser-certs](https://github.com/doccaz/update-browser-certs) | Syncs browser CA certificate stores with the system trust anchors |

### AI / MCP

| Repo | Description |
|---|---|
| [mcp-linux-diagnostics](https://github.com/doccaz/mcp-linux-diagnostics) | MCP server exposing Linux diagnostic tools to AI assistants like Claude |

### Linux & Desktop

| Repo | Description |
|---|---|
| [linux-kb](https://github.com/doccaz/linux-kb) | Personal knowledge base of Linux scripts and recipes (bash, kvm, btrfs, network, ldap, salt, SUMA, and more) |
| [keyring-setpass](https://github.com/doccaz/keyring-setpass) | Sets GNOME keyring passwords non-interactively for headless environments |

### Fun & Hobby

| Repo | Description |
|---|---|
| [knobcast](https://github.com/doccaz/knobcast) | ESP32-C3 + rotary encoder + OLED physical remote for Chromecast, with web UI and captive portal setup |
| [urnas-br](https://github.com/doccaz/urnas-br) | Downloads and analyzes Brazilian electronic voting machine data from the TSE public API |
| [meshprep](https://github.com/doccaz/meshprep) | Browser-based OBJ/STL mesh editor and 3D print optimizer for FDM and SLA printing |

---

## Setup

This is a plain static site — just `index.html`. GitHub Pages serves it automatically from the `main` branch of the `doccaz/doccaz.github.io` repository.

To enable GitHub Pages:

1. Create a repo named **`doccaz.github.io`** on GitHub.
2. Push `index.html` and `README.md` to the `main` branch.
3. GitHub Pages activates automatically — no extra configuration needed.

## Adding a new project

Edit `index.html` and add a new `<a class="card">` block inside the `<div class="grid">`. Set `data-tags` to a comma-separated list of applicable tags (`suse`, `kubernetes`, `virtualization`, `security`, `ai-mcp`, `monitoring`, `linux`, `fun`, `embedded`, `aws`). Tag chips are generated automatically — no need to add them manually.

## License

MIT
