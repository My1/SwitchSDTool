# SwitchSDTool - Modernized

## Todo

1) Proper Docs involving modern Tools.
2) change keys.txt to prod.keys
3) read mSD seed from there and try to use that
    * is this even possible, LPRCM does not dump the verification vector (the `private` file) on the mSD
4) used title.keys instead of a mounted/dumped SYSTEM Partition
5) Use a Logo that is less obviously a walking trademark violation

# SwitchSSDTool original README

This is a tool used to dump NSP files from the games/dlc/updates you legitimately obtained from the e-shop. This is done through obtaining a nand backup via [hekate](https://github.com/CTCaer/hekate/), the required console specific keys via [biskeydump](https://github.com/rajkosto/biskeydump) from your switch, along with other keys via [kezplez](https://github.com/tesnos/kezplez-nx) needed for [hactool](https://github.com/SciresM/hactool). It also requires [googling](https://www.google.com/ "Hoping kezplez eventually supports retrieving this") for eticket_rsa_kek. For minimal ban risk,  Delete your wifi connection profiles, put your switch into airplane mode,  *BACKUP YOUR NAND*, run biskeydump, follow the instructions for running kezplez to get keys.txt, *RESTORE YOUR NAND*. At the end of this, you will then need [hac disk mount](https://switchtools.sshnuke.net/) to dump PRODINFO.bin, and mount the SYSTEM partition.

![screensot](https://github.caitsith2.com/SwitchSDTool/screenshot_new.png)
