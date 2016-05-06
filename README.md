# Tools
Example output of pescanner.py
<pre>
################################################################################\n
Record 0
################################################################################

Meta-data
================================================================================
File:    ff48d847de384e7347ea82f3ba3e8aa06026d6c59d2466c9c12c05b519aed8ef
Size:    2780 bytes
Type:    PE32 executable (DLL) (GUI) Intel 80386, for MS Windows
MD5:     663826b257a5993ea7f1893f76a828fc
SHA1:    b447da837b138ecb0de37faab58f2b81967ac69b
SHA256:  ff48d847de384e7347ea82f3ba3e8aa06026d6c59d2466c9c12c05b519aed8ef
ssdeep:  12:eFGSGuXW0IldLlh6h1Ml0d2zjJgfyB/tfOuS:eFGS5aedGCgakzjmfekH
imphash: b20bbc4956ed445f436ec8c674fab104
Date:    0x534EA299 [Fri Apr  9 17:32:25 2014 UTC]
EP:      0x10001076 .text 0/4
CRC:     Claimed: 0x0, Actual: 0xf4e9 [SUSPICIOUS]
RichHdr: Checksum is valid!

Rich Header
================================================================================
@Comp.id       ID           Version      Count        Description
--------------------------------------------------------------------------------
0x00010000     01           0            8            [---] Unmarked objects
0x00937809     93           30729        3            [IMP] VS2008 SP1 build 30729
0x009d766f     9d           30319        1            [LNK] VS2010 build 30319
0x00af766f     af           30319        3            [---] Unknown

Sections
================================================================================
Name       VirtAddr     VirtSize     RawSize      Entropy
--------------------------------------------------------------------------------
.text      0x1000       0x86         0x200        2.118060
.rdata     0x2000       0x8c         0x200        1.359222
.data      0x3000       0x4          0x0          0.000000    [SUSPICIOUS]
.reloc     0x4000       0x34         0x200        0.149797    [SUSPICIOUS]
 </pre>
