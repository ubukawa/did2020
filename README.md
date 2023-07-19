# did2020
2020年国勢調査　人口集中地区データ（e-Statより）


# download data
PowerShell で
```
mkdir 01_src
get-content "download.txt" | Invoke-Expression
```