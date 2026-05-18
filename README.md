# scoop-dbxignore

[Scoop](https://scoop.sh) bucket for [dbxignore](https://github.com/kiloscheffer/dbxignore).

## Install

```powershell
scoop bucket add dbxignore https://github.com/kiloscheffer/scoop-dbxignore
scoop install dbxignore/dbxignore
```

After install, register the daemon:

```powershell
dbxignore install
```

`dbxignore install` creates a Task Scheduler entry that launches the daemon at every user logon. Run `dbxignore uninstall` before `scoop uninstall dbxignore` to remove the scheduled task cleanly.

## License

MIT
