<p align="center"><img src="imagens/banner.png" alt="FinderX" width="640"></p>

<p align="center"><a href="README.md">Português</a> · <b>English</b> · <a href="README.es.md">Español</a></p>

# FinderX

A file manager for **macOS** that works like the **Windows 11 File Explorer**: tabs, command bar, folder tree and the Windows shortcuts (with ⌘ in place of Ctrl). On top of that it brings things neither Finder nor File Explorer have, such as a **dual pane**, a **copy queue** and **copy verification**.

For people coming from Windows, people who use both systems, and anyone who works with lots of files and external drives.

> The app itself is in Brazilian Portuguese for now.

## Download

Get the latest version from **[Releases](https://github.com/dmanske/FinderX-public/releases/latest)**:

| Your computer | File |
|---|---|
| Mac with Apple silicon (M1, M2, M3, M4…) | `FinderX-<version>-Mac-chip-Apple.zip` |
| Mac with an Intel processor, or a Hackintosh | `FinderX-<version>-Hackintosh-Intel.zip` |

Requires **macOS 14 (Sonoma) or later**.

## Install

1. Open the `.zip` and drag **FinderX** into **Applications**.
2. The first time, macOS says it can't verify the app (it is not notarized by Apple). Open **System Settings ▸ Privacy & Security**, scroll to the FinderX notice and click **Open Anyway**.
3. To update, replace the app in Applications with the new version.

## What makes it different

### Dual pane
Two folders in the same window, **side by side** or **stacked**, like the classic file managers. Each side has its own tabs, its own view mode and, at the bottom, **its own disk** with the free space. Tab switches sides; copying or moving to the other side is a single command. You can **compare** the two folders (what exists on one side only, what is newer, what is different, even checking the contents) and **sync** them with a preview of what will happen before any file is touched. With **Navigate together**, entering a subfolder on one side enters the same one on the other. **Workspaces** save a set of tabs and sides to come back to later.

### Copy queue
Sent several folders, from several places, to the same external drive? Instead of all of them fighting over the disk at the same time (and all getting slow), they go into **a queue**: one finishes, the next one starts on its own. Copies between **different disks** still run at the same time. The copy window shows which ones are **QUEUED** and how many are ahead, with **Start now** and **Remove from queue**; the Activities panel lets you change the order; and the bottom bar shows "1 copying · 2 queued". It is on by default and can be turned off in Settings.

### Copies you can trust
- **Side-by-side conflicts:** when the name already exists, both files are shown side by side (size and date) so you can keep one, the other or both.
- **Copy verification:** after copying, FinderX reads the original and the copy again and compares the contents (SHA-256). By default it asks for large copies to another disk; in Settings you can make it always or never. When **moving** to another disk with verification on, the original is only deleted after the copy checks out; if something came out different (bad cable, faulty thumb drive), the original stays where it was.
- **Speed graph** and time remaining, like Windows, and **undo** (⌘Z) for copy, move, rename and delete.

### Shelf
A floating basket to **gather files from several folders and disks** while you browse, and then move, copy, share or compress everything at once. It only remembers where each file is; nothing moves until you say so.

### The Windows way
Enter opens, F2 renames, ⌫ goes back, real **cut and paste**, Send to, Copy to… and Move to… with folder search, an address bar with clickable breadcrumbs (where you can also type a path), This PC with a space bar for each disk, date groups just like Windows. Shortcuts can be changed in Settings.

### Viewing and finding
- Details, Icons (extra large to small), List, Tiles, Content and Gallery; the **▸ arrow** opens a folder inside the list itself; columns adapt to the window width, with no blank space left over.
- **Rubber-band selection** in any direction, bottom to top included.
- **Search** with AND, OR, NOT and filters such as `tipo:pdf`; **text inside photos and scanned PDFs**, read on the Mac itself, no internet.
- **History on the Back button:** hold ‹ to see where you have been.

### Tools
- **What takes up space:** shows what weighs the most in a folder or disk.
- **Find duplicate files.**
- **Guided cleanup:** tidy up a full folder (like Downloads) one file at a time, keyboard only.
- **.zip, .7z and .tar opened as folders**, without extracting everything.
- **Delete permanently** with a reinforced question that shows the name and the location of what will be gone.
- **Trash and Cloud** inside the app: restore to the original place, see what is cloud-only, download or free up space.

### Network
Computers and shares on the local network in the tree, connect to a server and **Screen Sharing**.

### Appearance
**Mac Glass** or **Windows Mica**, light, dark or automatic, with or without transparency.

### Built not to freeze
If a disk stops responding (faulty thumb drive, stuck driver, dropped network), clicking the window and switching sides no longer freeze FinderX because of it.

## Screenshots

<p><img src="imagens/lado-a-lado-claro.png" alt="Dual pane side by side, each side's disk at the bottom"></p>
<p><img src="imagens/lado-a-lado-escuro.png" alt="Dual pane in dark mode"></p>
<p><img src="imagens/mica.png" alt="Windows Mica appearance"></p>
<p><img src="imagens/fila.png" alt="Copy queue: the second copy waits for the same disk"></p>
<p><img src="imagens/sobre.png" alt="About FinderX window" width="560"></p>

## Problems and suggestions

Open an **[Issue](https://github.com/dmanske/FinderX-public/issues)** describing what happened, the FinderX version (FinderX menu ▸ Sobre o FinderX) and your macOS version.

## License

[MIT](LICENSE) · © 2026 Daniel Manske.

FinderX is not affiliated with Microsoft or Apple. Windows is a trademark of Microsoft; Finder and macOS are trademarks of Apple. No Microsoft code or icons were copied: the behavior was reproduced from use.
