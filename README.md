Forked from v110 of [TheFreeman193's repo](https://github.com/TheFreeman193/PIFS) with minor changes:

- Ensure correct starting directory `/data/adb/pifs`, script must be installed in this directory.
- If run with `-c`, assume non-interactive mode, since prints are highly likely to still be working. This also allows running 'head-less', e.g. via Tasker shortcut.
