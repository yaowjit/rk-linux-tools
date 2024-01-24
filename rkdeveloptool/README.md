v1.32

```
---------------------Tool Usage ---------------------
Help:             -h     or  --help
Version:          -v     or  --version
ListDevice:       ld
DownloadBoot:     db     <Loader>
UpgradeLoader:    ul     <Loader>
ReadLBA:          rl     <BeginSec>      <SectorLen> <File>
WriteLBA:         wl     <BeginSec>      <File>
WriteLBA:         wlx    <PartitionName> <File>
WriteGPT:         gpt    <gpt            partition   table>
WriteParameter:   prm    <parameter>
PrintPartition:   ppt
EraseFlash:       ef
TestDevice:       td
ResetDevice:      rd     [subcode]
ReadFlashID:      rid
ReadFlashInfo:    rfi
ReadChipInfo:     rci
ReadCapability:   rcb
PackBootLoader:   pack
UnpackBootLoader: unpack <boot           loader>
TagSPL:           tagspl <tag>           <U-Boot     SPL>
-------------------------------------------------------

```
