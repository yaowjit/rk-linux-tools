v2.4

```b
---------------------Tool Usage ---------------------
Help:             H
Quit:             Q
Version:          V
Clear Screen:     CS
------------------Upgrade Command ------------------
ChooseDevice:    CD
ListDevice:      LD
SwitchDevice:    SD
UpgradeFirmware: UF  <Firmware> [-noreset]
UpgradeLoader:   UL  <Loader>   [-noreset] [FLASH|EMMC|SPINOR|SPINAND]
DownloadImage:   DI  <-p|-b|-k|-s|-r|-m|-u|-t|-re image>
DownloadBoot:    DB  <Loader>
EraseFlash:      EF  <Loader|firmware>
PartitionList:   PL
WriteSN:         SN  <serial number>
ReadSN:          RSN
ReadComLog:      RCL <File>
CreateGPT:       GPT <Input Parameter> <Output Gpt>
SwitchStorage:   SSD
----------------Professional Command -----------------
TestDevice:     TD
ResetDevice:    RD  [subcode]
ResetPipe:      RP  [pipe]
ReadCapability: RCB
ReadFlashID:    RID
ReadFlashInfo:  RFI
ReadChipInfo:   RCI
ReadSecureMode: RSM
ReadSector:     RS  <BeginSec>   <SectorLen>  [-decode]   [File]
WriteSector:    WS  <BeginSec>   <File>
ReadLBA:        RL  <BeginSec>   <SectorLen>  [File]
WriteLBA:       WL  <BeginSec>   [SizeSec]    <File>
EraseLBA:       EL  <BeginSec>   <EraseCount>
EraseBlock:     EB  <CS>         <BeginBlock> <BlokcLen>  [--Force]
RunSystem:      RUN <uboot_addr> <trust_addr> <boot_addr> <uboot> <trust> <boot>
-------------------------------------------------------

```
