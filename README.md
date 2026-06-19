# scoop-bucket

A [Scoop](https://scoop.sh) bucket for [`bdinfo-rs`](https://github.com/agentjp/bdinfo-rs) —
a memory-safe, statically-linked command-line Blu-ray disc analyzer (a drop-in
replacement for the classic BDInfo tool).

```powershell
scoop bucket add agentjp https://github.com/agentjp/scoop-bucket
scoop install bdinfo-rs
```

The manifest tracks upstream GitHub releases automatically via the daily
[Excavator](.github/workflows/excavator.yml) workflow (`checkver` + `autoupdate`).
