# **Digitnext_Ultra Developer Hardware Reference**
Detailed device information for ROM/kernel development: system partitions, thermal & voltage sensors, camera, SoC specs, network, and supported features.


## GENERAL

| Manufacturer   | Digit                                                                                                                                                                                    |
| -------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Model          | Digitnext_Ultra                                                                                                                                                                          |
| Brand          | Digit                                                                                                                                                                                    |
| Vendor         | Imagination Technologies                                                                                                                                                                 |
| Resolution     | 1600 × 720                                                                                                                                                                               |
| Platform       | MediaTek MT6762                                                                                                                                                                          |
| Android        | 13                                                                                                                                                                                       |
| API Level      | 33                                                                                                                                                                                       |
| LCM            | icnl9911c_hd1600_dsi_vdo_txd                                                                                                                                                             |
| Touchscreen    | chipone-tddi (i2c 0-0041)                                                                                                                                                                |
| Accelerometer  | ACCELEROMETER                                                                                                                                                                            |
| ALS / PS       | LIGHT                                                                                                                                                                                    |
| Charger        | PMIC-controlled                                                                                                                                                                          |
| PMIC           | mt6370_pmu (i2c 5-0034)                                                                                                                                                                  |
| Fingerprint    | silead_fp_spi (spi0.0)                                                                                                                                                                   |
| Wi-Fi          | CONSYS_MT6765                                                                                                                                                                            |
| Sound          | mt63xx-accdet                                                                                                                                                                            |
| RAM            | 4 GB                                                                                                                                                                                     |
| Flash          | Samsung RH64MB                                                                                                                                                                           |
| Flash Size     | 64 GB                                                                                                                                                                                    |
| Kernel         | 4.19.191 - Android (6443078, based on r383902)                                                                                                                                           |
|                | clang 11.0.1 - LLD 11.0.1                                                                                                                                                                |
|                | Build: #1 SMP PREEMPT Thu Jan 11 17:01:46 CST 2024                                                                                                                                       |
|                |                                                                                                                                                                                          |
| Kernel Cmdline | 4.19.191 (Android (6443078 based on r383902) <br>clang version 11.0.1 (https://android.googlesource.com/toolchain/llvm-project), LLD 11.0.1  #1 SMP PREEMPT Thu Jan 11 17:01:46 CST 2024 |
## SOC
| Parameter          | Specification                                            |
| ------------------ | -------------------------------------------------------- |
| SoC                | Helio P22                                                |
| CPU                | MT6762V/CB                                               |
| Vendor             | MediaTek                                                 |
| Model              | MT6762                                                   |
| Cores              | 8                                                        |
| big.LITTLE         | 2 clusters                                               |
| Clusters           | 4 × 2.00 GHz, 4 × 1.50 GHz                               |
| Family             | Cortex-A53                                               |
| Mode               | 64-bit                                                   |
| Machine            | aarch64                                                  |
| ABI                | arm64-v8a                                                |
| Instructions       | fp, asimd, evtstrm, aes, pmull, sha1, sha2, crc32, cpuid |
| Process technology | 12 nm                                                    |
| Revision           | r0p4                                                     |
| CPU Clock speed    | 400 – 2001 MHz                                           |
| GPU                | PowerVR Rogue GE8320                                     |
| GPU Vendor         | Imagination Technologies                                 |
| OpenGL ES          | 3.2 build 1.13@5776728                                   |
| Vulkan             | 1.1                                                      |
| GPU Clock speed    | 400 – 650 MHz                                            |
## SYSTEM
| Parameter            | Specification                                |
| -------------------- | -------------------------------------------- |
| Manufacturer         | Digit                                        |
| Model                | Digitnext_Ultra                              |
| Brand                | Digit                                        |
| Android Version      | 13                                           |
| API Level            | 33                                           |
| Codename             | Tiramisu                                     |
| Device               | Digitnext_Ultra                              |
| Product              | Digitnext_Ultra                              |
| Board                | k62v1_64_bsp                                 |
| Build ID             | SP1A.210812.016                              |
| Java VM              | ART 2.1.0                                    |
| Security Patch       | 2024-01-01                                   |
| Baseband             | MOLY.LR12A.R3.MP.V298, MOLY.LR12A.R3.MP.V298 |
| GPS                  | MTK_MNLD_default, MNL_VER_default / 2020     |
| Build Type           | user                                         |
| Build Tags           | release-keys                                 |
| Incremental          | 1704853980                                   |
| Build Date           | 2024-01-16                                   |
| Builder              | yang@yang-PC                                 |
| Google Play Services | 25.47.30 (190400-833691957)                  |

## **BUILD FINGERPRINT**

| ro.system.build.fingerprint      | Digit/Digitnext_Ultra/Digitnext_Ultra:13/SP1A.210812.016/1704853980:user/release-keys<br> |
| -------------------------------- | ----------------------------------------------------------------------------------------- |
| ro.vendor.build.fingerprint      | Digit/Digitnext_Ultra/Digitnext_Ultra:12/SP1A.210812.016/1704853980:user/release-keys<br> |
| ro.odm.build.fingerprint         | Digit/Digitnext_Ultra/Digitnext_Ultra:12/SP1A.210812.016/1704853980:user/release-keys<br> |
| ro.product.build.fingerprint     | Digit/Digitnext_Ultra/Digitnext_Ultra:13/SP1A.210812.016/1704853980:user/release-keys<br> |
| ro.system_ext.build.fingerprint  | Digit/Digitnext_Ultra/Digitnext_Ultra:13/SP1A.210812.016/1704853980:user/release-keys<br> |
| ro.system_dlkm.build.fingerprint | Digit/Digitnext_Ultra/Digitnext_Ultra:13/SP1A.210812.016/1704853980:user/release-keys<br> |
| ro.odm_dlkm.build.fingerprint    | Digit/Digitnext_Ultra/Digitnext_Ultra:12/SP1A.210812.016/1704853980:user/release-keys<br> |
| ro.vendor_dlkm.build.fingerprint | Digit/Digitnext_Ultra/Digitnext_Ultra:12/SP1A.210812.016/1704853980:user/release-keys<br> |
| ro.bootimage.build.fingerprint   | Digit/Digitnext_Ultra/Digitnext_Ultra:12/SP1A.210812.016/1704853980:user/release-keys     |

## SCREEN
| Parameter    | Specification                |
| ------------ | ---------------------------- |
| Resolution   | 1600 × 720                   |
| Ratio        | 20:9                         |
| Diagonal     | ~6.51 – 6.54" / 165 – 166 mm |
| Size         | 65 × 152 mm                  |
| Density      | 320 (xhdpi)                  |
| X DPI        | 282                          |
| Y DPI        | 267                          |
| PPI          | 270                          |
| Refresh rate | 60.0 Hz                      |
| Modes        | 720 × 1600 @ 60.0 Hz         |

## CAMERA

| Model     | 13.0 MP <br>Samsung     s5k3l2_mipiraw  <br>BYD              bf2553l_mipiraw  <br>BYD              bf20a1_mipiraw  <br>BYD              bf20a1_mipiraw                                            |
| --------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Supported | 13.0 MP Samsung s5k3l2_mipi_raw  <br>5.0 MP GalaxyCore gc5035_mipi_raw  <br>2.0 MP BYD bf2253l_mipi_raw  <br>0.3 MP GalaxyCore gc030a_mipi_raw  <br>BYD bf20a1_mipi_raw  <br>BYD bf2553l_mipi_raw |
## BATTERY

| Parameter      | Specification      |
| -------------- | ------------------ |
| Technology     | Li-ion             |
| Voltage        | 4417 mV            |
| Fast Charge    | Slow Charging only |
| Power Profile  | 5000 mAh           |
| Kernel Profile | 2946 mAh           |
## THERMAL
| Sensor        | Temperature |
| ------------- | ----------- |
| mtktsbattery  | 23.4 °C     |
| mtktsAP       | 26.0 °C     |
| mtktsbtsmdpa  | 24.0 °C     |
| mtktscpu      | 30.6 °C     |
| mtktswmt      | 25.0 °C     |
| mtktspmic     | 28.4 °C     |
| mt6357tsbuck1 | 26.2 °C     |
| mt6357tsbuck2 | 28.3 °C     |
| battery       | 23.4 °C     |
| mtktscharger  | 26.0 °C     |

# PARTITIONS

## Table 1: /dev/block/by-name partitions
| NAME            | FS Type | Maj/Min | Total Blocks | Block Start | Block End   | Size (Bytes)   | Size (MiB) | by-name                            | Symlink                 |
| --------------- | ------- | ------- | ------------ | ----------- | ----------- | -------------- | ---------- | ---------------------------------- | ----------------------- |
| preloader_raw_a | raw     | 252:35  | 8188         | 0           | 8187        | 4,192,256      | 3.99M      | /dev/block/by-name/preloader_raw_a | /dev/block/dm-35        |
| preloader_raw_b | raw     | 252:36  | 8188         | 0           | 8187        | 4,192,256      | 3.99M      | /dev/block/by-name/preloader_raw_b | /dev/block/dm-36        |
| mmcblk0boot0    | raw     | 179:32  | 8192         | 0           | 8191        | 4,194,304      | 4.00M      | /dev/block/by-name/mmcblk0boot0    | /dev/block/mmcblk0boot0 |
| preloader_a     | raw     | 179:32  | 8192         | 0           | 8191        | 4,194,304      | 4.00M      | /dev/block/by-name/preloader_a     | /dev/block/mmcblk0boot0 |
| mmcblk0boot1    | raw     | 179:64  | 8192         | 0           | 8191        | 4,194,304      | 4.00M      | /dev/block/by-name/mmcblk0boot1    | /dev/block/mmcblk0boot1 |
| preloader_b     | raw     | 179:64  | 8192         | 0           | 8191        | 4,194,304      | 4.00M      | /dev/block/by-name/preloader_b     | /dev/block/mmcblk0boot1 |
| mmcblk0         | raw     | 179:0   | 122,142,720  | 0           | 122,142,719 | 62,537,072,640 | 59,640.00M | /dev/block/by-name/mmcblk0         | /dev/block/mmcblk0      |
| boot_para       | raw     | 179:1   | 2048         | 64          | 2111        | 1,048,576      | 1.00M      | /dev/block/by-name/boot_para       | /dev/block/mmcblk0p1    |
| para            | raw     | 179:2   | 1024         | 2112        | 3135        | 524,288        | 0.50M      | /dev/block/by-name/para            | /dev/block/mmcblk0p2    |
| expdb           | raw     | 179:3   | 40,960       | 3136        | 44,095      | 20,971,520     | 20.00M     | /dev/block/by-name/expdb           | /dev/block/mmcblk0p3    |
| frp             | raw     | 179:4   | 2048         | 44,096      | 46,143      | 1,048,576      | 1.00M      | /dev/block/by-name/frp             | /dev/block/mmcblk0p4    |
| nvcfg           | ext4    | 179:5   | 65,536       | 46,144      | 111,679     | 33,554,432     | 32.00M     | /dev/block/by-name/nvcfg           | /dev/block/mmcblk0p5    |
| nvdata          | ext4    | 179:6   | 131,072      | 111,680     | 242,751     | 67,108,864     | 64.00M     | /dev/block/by-name/nvdata          | /dev/block/mmcblk0p6    |
| md_udc          | ext4    | 179:7   | 46,288       | 242,752     | 289,039     | 23,699,456     | 22.60M     | /dev/block/by-name/md_udc          | /dev/block/mmcblk0p7    |
| metadata        | raw     | 179:8   | 65,536       | 289,040     | 354,575     | 33,554,432     | 32.00M     | /dev/block/by-name/metadata        | /dev/block/mmcblk0p8    |
| protect1        | ext4    | 179:9   | 16,384       | 354,576     | 370,959     | 8,388,608      | 8.00M      | /dev/block/by-name/protect1        | /dev/block/mmcblk0p9    |
| protect2        | ext4    | 179:10  | 22,256       | 370,960     | 393,215     | 11,395,072     | 10.86M     | /dev/block/by-name/protect2        | /dev/block/mmcblk0p10   |
| seccfg          | raw     | 179:11  | 16,384       | 393,216     | 409,599     | 8,388,608      | 8.00M      | /dev/block/by-name/seccfg          | /dev/block/mmcblk0p11   |
| persist         | ext4    | 179:12  | 98,304       | 409,600     | 507,903     | 50,331,648     | 48.00M     | /dev/block/by-name/persist         | /dev/block/mmcblk0p12   |
| sec1            | raw     | 179:13  | 4,096        | 507,904     | 511,999     | 2,097,152      | 2.00M      | /dev/block/by-name/sec1            | /dev/block/mmcblk0p13   |
| proinfo         | raw     | 179:14  | 6,144        | 512,000     | 518,143     | 3,145,728      | 3.00M      | /dev/block/by-name/proinfo         | /dev/block/mmcblk0p14   |
| nvram           | raw     | 179:15  | 131,072      | 518,144     | 649,215     | 67,108,864     | 64.00M     | /dev/block/by-name/nvram           | /dev/block/mmcblk0p15   |
| logo            | raw     | 179:16  | 22,528       | 649,216     | 671,743     | 11,534,336     | 11.00M     | /dev/block/by-name/logo            | /dev/block/mmcblk0p16   |
| md1img_a        | raw     | 179:17  | 204,800      | 671,744     | 876,543     | 104,857,600    | 100.00M    | /dev/block/by-name/md1img_a        | /dev/block/mmcblk0p17   |
| spmfw_a         | raw     | 179:18  | 2,048        | 876,544     | 878,591     | 1,048,576      | 1.00M      | /dev/block/by-name/spmfw_a         | /dev/block/mmcblk0p18   |
| scp_a           | raw     | 179:19  | 2,048        | 878,592     | 880,639     | 1,048,576      | 1.00M      | /dev/block/by-name/scp_a           | /dev/block/mmcblk0p19   |
| sspm_a          | raw     | 179:20  | 2,048        | 880,640     | 882,687     | 1,048,576      | 1.00M      | /dev/block/by-name/sspm_a          | /dev/block/mmcblk0p20   |
| gz_a            | raw     | 179:21  | 32,768       | 882,688     | 915,455     | 16,777,216     | 16.00M     | /dev/block/by-name/gz_a            | /dev/block/mmcblk0p21   |
| lk_a            | raw     | 179:22  | 2,048        | 915,456     | 917,503     | 1,048,576      | 1.00M      | /dev/block/by-name/lk_a            | /dev/block/mmcblk0p22   |
| boot_a          | raw     | 179:23  | 196,608      | 917,504     | 1,114,111   | 100,663,296    | 96.00M     | /dev/block/by-name/boot_a          | /dev/block/mmcblk0p23   |
| init_boot_a     | raw     | 179:24  | 16,384       | 1,114,112   | 1,130,495   | 8,388,608      | 8.00M      | /dev/block/by-name/init_boot_a     | /dev/block/mmcblk0p24   |
| dtbo_a          | raw     | 179:25  | 16,384       | 1,130,496   | 1,146,879   | 8,388,608      | 8.00M      | /dev/block/by-name/dtbo_a          | /dev/block/mmcblk0p25   |
| tee_a           | raw     | 179:26  | 10,240       | 1,146,880   | 1,157,119   | 5,242,880      | 5.00M      | /dev/block/by-name/tee_a           | /dev/block/mmcblk0p26   |
| vbmeta_a        | raw     | 179:27  | 16,384       | 1,157,120   | 1,173,503   | 8,388,608      | 8.00M      | /dev/block/by-name/vbmeta_a        | /dev/block/mmcblk0p27   |
| vbmeta_system_a | raw     | 179:28  | 16,384       | 1,173,504   | 1,189,887   | 8,388,608      | 8.00M      | /dev/block/by-name/vbmeta_system_a | /dev/block/mmcblk0p28   |
| vbmeta_vendor_a | raw     | 179:29  | 22,528       | 1,189,888   | 1,212,415   | 11,534,336     | 11.00M     | /dev/block/by-name/vbmeta_vendor_a | /dev/block/mmcblk0p29   |
| md1img_b        | raw     | 179:30  | 204,800      | 1,212,416   | 1,417,215   | 104,857,600    | 100.00M    | /dev/block/by-name/md1img_b        | /dev/block/mmcblk0p30   |
| spmfw_b         | raw     | 179:31  | 2,048        | 1,417,216   | 1,419,263   | 1,048,576      | 1.00M      | /dev/block/by-name/spmfw_b         | /dev/block/mmcblk0p31   |
| scp_b           | raw     | 259:0   | 2,048        | 1,419,264   | 1,421,311   | 1,048,576      | 1.00M      | /dev/block/by-name/scp_b           | /dev/block/mmcblk0p32   |
| sspm_b          | raw     | 259:1   | 2,048        | 1,421,312   | 1,423,359   | 1,048,576      | 1.00M      | /dev/block/by-name/sspm_b          | /dev/block/mmcblk0p33   |
| gz_b            | raw     | 259:2   | 32,768       | 1,423,360   | 1,456,127   | 16,777,216     | 16.00M     | /dev/block/by-ame/ngz_b            | /dev/block/mmcblk0p34   |
| lk_b            | raw     | 259:3   | 2,048        | 1,456,128   | 1,458,175   | 1,048,576      | 1.00M      | /dev/block/by-name/lk_b            | /dev/block/mmcblk0p35   |
| boot_b          | raw     | 259:4   | 196,608      | 1,458,176   | 1,654,783   | 100,663,296    | 96.00M     | /dev/block/by-name/boot_b          | /dev/block/mmcblk0p36   |
| init_boot_b     | raw     | 259:5   | 16,384       | 1,654,784   | 1,671,167   | 8,388,608      | 8.00M      | /dev/block/by-name/init_boot_b     | /dev/block/mmcblk0p37   |
| dtbo_b          | raw     | 259:6   | 16,384       | 1,671,168   | 1,687,551   | 8,388,608      | 8.00M      | /dev/block/by-name/dtbo_b          | /dev/block/mmcblk0p38   |
| tee_b           | raw     | 259:7   | 16,384       | 1,687,552   | 1,703,935   | 8,388,608      | 8.00M      | /dev/block/by-name/tee_b           | /dev/block/mmcblk0p39   |
| super           | raw     | 259:8   | 11,816,960   | 1,703,936   | 13,520,895  | 6,050,283,520  | 5.63G      | /dev/block/by-name/super           | /dev/block/mmcblk0p40   |
| vbmeta_b        | raw     | 259:9   | 16,384       | 13,520,896  | 13,537,279  | 8,388,608      | 8.00M      | /dev/block/by-name/vbmeta_b        | /dev/block/mmcblk0p41   |
| vbmeta_system_b | raw     | 259:10  | 16,384       | 13,537,280  | 13,553,663  | 8,388,608      | 8.00M      | /dev/block/by-name/vbmeta_system_b | /dev/block/mmcblk0p42   |
| vbmeta_vendor_b | raw     | 259:11  | 28,672       | 13,553,664  | 13,582,335  | 14,680,064     | 14.00M     | /dev/block/by-name/vbmeta_vendor_b | /dev/block/mmcblk0p43   |
| userdata        | raw     | 259:12  | 108,439,488  | 13,582,336  | 122,021,823 | 55,521,017,856 | 52,948.96M | /dev/block/by-name/userdata        | /dev/block/mmcblk0p44   |
| otp             | raw     | 259:13  | 88,064       | 122,021,824 | 122,109,887 | 45,088,768     | 43.00M     | /dev/block/by-name/otp             | /dev/block/mmcblk0p45   |
| flashinfo       | raw     | 259:14  | 32,768       | 122,109,888 | 122,142,655 | 16,777,216     | 16.00M     | /dev/block/by-name/flashinfo       | /dev/block/mmcblk0p46   |

## Table 2: Device Mapper (dm-*) partitions

| DM Device        | Name             | Maj/Min | Total Blocks | Size (Bytes)   | Size (MiB) | By-Name                            | Links Back To |
| ---------------- | ---------------- | ------- | ------------ | -------------- | ---------- | ---------------------------------- | ------------- |
| /dev/block/dm-0  | product_a        | 252:0   | 4,561,760    | 2,335,621,120  | 2,227.42M  |                                    | mmcblk0p40    |
| /dev/block/dm-1  | system_a         | 252:1   | 3,684,448    | 1,886,437,376  | 1.75G      |                                    | mmcblk0p40    |
| /dev/block/dm-2  | system_b         | 252:2   | 470,280      | 240,783,360    | 229.62M    |                                    | mmcblk0p40    |
| /dev/block/dm-3  | vendor_a         | 252:3   | 1,051,304    | 538,267,648    | 513.33M    |                                    | mmcblk0p40    |
| /dev/block/dm-14 | com.android.wifi | 252:14  | 15,784       | 8,081,408      | 7.70M      |                                    | loop34        |
| /dev/block/dm-34 | userdata         | 252:34  | 108,439,488  | 55,521,017,856 | 52,948.96M |                                    | mmcblk0p44    |
| /dev/block/dm-35 | pl_a             | 252:35  | 8,188        | 4,192,256      | 3.99M      | /dev/block/by-name/preloader_raw_a | mmcblk0boot0  |
| /dev/block/dm-36 | pl_b             | 252:36  | 8,188        | 4,192,256      | 3.99M      | /dev/block/by-name/preloader_raw_b | mmcblk0boot1  |
## Table 3:  SPFlash Tool - Partition layout
*Flashable partitions with spflash tool as per ORIGINAL Scatter file:*

| Partition Name  | File Name           | Type       | Operation Type | Upgradable |
| --------------- | ------------------- | ---------- | -------------- | ---------- |
| boot_a          | boot_a.img          | NORMAL_ROM | UPDATE         | true       |
| dtbo_a          | dtbo_a.img          | NORMAL_ROM | UPDATE         | true       |
| gz_a            | gz_a.img            | NORMAL_ROM | UPDATE         | true       |
| init_boot_a     | init_boot_a.img     | NORMAL_ROM | UPDATE         | true       |
| lk_a            | lk_a.img            | NORMAL_ROM | UPDATE         | true       |
| logo            | logo.bin            | NORMAL_ROM | UPDATE         | true       |
| md1img_a        | md1img_a.img        | NORMAL_ROM | UPDATE         | true       |
| preloader       | preloader.bin       | SV5_BL_BIN | BOOTLOADERS    | false      |
| scp_a           | scp_a.img           | NORMAL_ROM | UPDATE         | true       |
| spmfw_a         | spmfw_a.img         | NORMAL_ROM | UPDATE         | true       |
| sspm_a          | sspm_a.img          | NORMAL_ROM | UPDATE         | true       |
| super           | super.img           | NORMAL_ROM | UPDATE         | true       |
| tee_a           | tee_a.img           | NORMAL_ROM | UPDATE         | true       |
| userdata        | userdata.img        | EXT4_IMG   | UPDATE         | true       |
| vbmeta_a        | vbmeta_a.img        | NORMAL_ROM | UPDATE         | true       |
| vbmeta_system_a | vbmeta_system_a.img | NORMAL_ROM | UPDATE         | true       |
| vbmeta_vendor_a | vbmeta_vendor_a.img | NORMAL_ROM | UPDATE         | true       |
| vendor_boot_a   | vendor_boot_a.img   | NORMAL_ROM | UPDATE         | true       |
*Note: vendor_boot_a was deleted and merged in boot_a to increase size (here its written as per scatter file*

## DRIVERS

| CAM_CAL_DRV            | DISPSYS                 | Routing-Control         | Vcodec                    | accel_hub_pl                  | alarmtimer                     |
| ---------------------- | ----------------------- | ----------------------- | ------------------------- | ----------------------------- | ------------------------------ |
| als_ps                 | alsps_hub_pl            | amms                    | atf_logger                | camera-dpe                    | camera-fdvt                    |
| camera-isp             | ccci_auxadc             | ccci_hif_ccif           | ccci_hif_cldma            | ccu                           | charger                        |
| cirq                   | clk-mt6765              | clk-mt6765-audio        | clk-mt6765-cam            | clk-mt6765-img                | clk-mt6765-mipi0a              |
| clk-mt6765-mm          | clk-mt6765-scpsys       | clk-mt6765-vcodec       | devapc                    | driver_modem                  | dvfsp                          |
| emi_clk_test           | emi_ctrl                | flashlight              | flashlights-mt6370        | fm                            | ged                            |
| gpio-keys              | gpufreq                 | gsensor                 | hps                       | image_sensor                  | ion-drv                        |
| leds-mt65xx            | lens_actuator_main2_af  | lens_actuator_main3_af  | lens_actuator_main_af     | lens_actuator_sub2_af         | lens_actuator_sub_af           |
| low_battery_throttling | m4u                     | masp                    | mediatek,devinfo          | mt-cpufreq                    | mt-eem                         |
| mt-freqhopping         | mt-i2c                  | mt-pmic-pwrap           | mt-ppm                    | mt-soc-dai-driver             | mt-soc-deep-buffer-dl-pcm      |
| mt-soc-dl1-awb-pcm     | mt-soc-dl1-pcm          | mt-soc-dl2-pcm          | mt-soc-dummy-codec        | mt-soc-dummy-pcm              | mt-soc-fm-i2s-awb-pcm          |
| mt-soc-fm-i2s-pcm      | mt-soc-fmmrgtx-pcm      | mt-soc-hp-impedence-pcm | mt-soc-i2s0-pcm           | mt-soc-i2s0awb-pcm            | mt-soc-i2s0dl1-pcm             |
| mt-soc-i2s2_adc2-pcm   | mt-soc-mrgrx-awb-pcm    | mt-soc-mrgrx-pcm        | mt-soc-routing-pcm        | mt-soc-tdmrx-pcm              | mt-soc-ul1-pcm                 |
| mt-soc-ul2-pcm         | mt-soc-uldlloopback-pcm | mt-soc-voice-usb        | mt-soc-voice-usb-echoref  | mt-soc-voicemd1               | mt-soc-voicemd1-bt             |
| mt-soc-voicemd2        | mt-soc-voicemd2-bt      | mt-soc-voip-bt-in       | mt-soc-voip-bt-out        | mt6357-charger-type-detection | mt6357-regulator               |
| mt6357-sound           | mt6357_gauge            | mt6357_ts_buck1         | mt6357_ts_buck2           | mt6359-efuse                  | mt635x-auxadc                  |
| mt6370_pmu_bled        | mt6370_pmu_charger      | mt6370_pmu_core         | mt6370_pmu_dsv            | mt6370_pmu_fled               | mt6370_pmu_ldo                 |
| mt6397                 | mt6397-rtc              | mt63xx-oc-debug         | mt6577-auxadc             | mt6577-uart                   | mt6761-qos                     |
| mt6765-cm_mgr          | mt6765-pinctrl          | mt6765-sspm             | mt67xx_rng                | mt_udi                        | mt_usb                         |
| mtboard-thermistor1    | mtboard-thermistor2     | mtk-audio               | mtk-btcvsd-snd            | mtk-clock-buffer              | mtk-dram_ctrl                  |
| mtk-dvfsrc             | mtk-dvfsrc-debug        | mtk-dvfsrc-met          | mtk-dvfsrc-up             | mtk-extcon-usb                | mtk-kpd                        |
| mtk-msdc               | mtk-pmic-keys           | mtk-smi-common          | mtk-smi-larb              | mtk-spi                       | mtk-thermal-legacy             |
| mtk-tpd                | mtk-tphy                | mtk-wdt                 | mtk_battery_oc_throttling | mtk_btif                      | mtk_cmdq                       |
| mtk_cmdq_mbox          | mtk_cmdq_tee_mbox       | mtk_connfem             | mtk_dbgtop                | mtk_disp_mgr                  | mtk_dynamic_loading_throttling |
| mtk_jpeg               | mtk_mmdvfs_pmqos        | mtk_ts_pmic             | mtk_uart_apdma            | mtk_wmt                       | mtkfb                          |
| mtktscharger           | mtktscharger2           | musb-hdrc               | nanohub_ipi               | pd                            | pd_adapter                     |
| perfmgr                | plat_sram_flag          | pmic-codec-accdet       | pmic_lbat_service         | pvrsrvkm                      | ramoops                        |
| reg-dummy              | regulator_vibrator      | rt-flash-led            | rt-pd-manager             | scp                           | scpdvfs                        |
| scpsys                 | sensor_hub_pl           | serial8250              | snd-soc-dummy             | spm                           | step_counter                   |
| sys_timer              | syscon-reboot-mode      | systracker              | tee_sanity                | trusted_mem                   | trusty                         |
| trusty-gz-log          | trusty-irq              | trusty-virtio           | trusty_gz                 | usb_phy_generic               | utos                           |
| wlan                   |                         |                         |                           |                               |                                |

## PMIC
| Name         | Voltage | Name         | Voltage |
| ------------ | ------- | ------------ | ------- |
| vs1          | 2.100 V | vemc         | 3.000 V |
| vcn18        | 1.800 V | vcore        | 0.700 V |
| vdram        | 1.200 V | vio18        | 1.800 V |
| vio28        | 2.800 V | vproc        | 0.781 V |
| vsim2        | 3.000 V | vxo22        | 2.200 V |
| vaud28       | 2.800 V | vaux18       | 1.800 V |
| vmodem       | 0.700 V | vusb33       | 3.000 V |
| dsv_neg      | 5.750 V | dsv_pos      | 5.750 V |
| vcn33_bt     | 3.300 V | vsram_proc   | 0.881 V |
| vsram_others | 0.900 V | vmc          | 3.000 V |
| vpa          | 0.500 V | vibr         | 2.800 V |
| vmch         | 3.000 V | vcama        | 2.800 V |
| vcamd        | 1.200 V | vcn28        | 2.800 V |
| vfe28        | 2.800 V | vrf12        | 1.200 V |
| vrf18        | 1.800 V | vsim1        | 3.000 V |
| vcamio       | 1.800 V | vefuse       | 1.800 V |
| vldo28       | 2.800 V | irtx_ldo     | 3.400 V |
| vcn33_wifi   | 3.300 V | usb-otg-vbus | 5.050 V |

## WI-FI
| Parameter    | Value                     |
| ------------ | ------------------------- |
| IPv4         | 192.168.100.62            |
| IPv6         | fe80::d88d:4aff:fe1f:f189 |
| Link Speed   | 175 Mbps                  |
| Standard     | 802.11ac                  |
| Frequency    | 5745 MHz                  |
| Channel      | 149                       |
| Signal       | −83 dBm                   |
| Level        | 37 %                      |
| Band 5 GHz   | Yes                       |
| Band 6 GHz   | No                        |
| Wi-Fi Direct | Yes                       |
| WPA3         | Yes                       |

## INPUT
| Name                        | ID | Vendor | Product | Extra Info      | Hash                                       |
| --------------------------- | -- | ------ | ------- | --------------- | ------------------------------------------ |
| **mtk-pmic-keys**           | 2  | 1      | 1       | —               | `485d69228e24f5e46da1598745890b214130dbc4` |
| **mtk-kpd**                 | 3  | 0      | 0       | —               | `9a244e01c90550ca2eb2798ffe20d8731e811765` |
| **mtk-tpd**                 | 4  | 0      | 0       | Touch: 1600×720 | `84931e976ab60191371c1c95baf408538ca4c4c5` |
| **mt63xx-accdet (Headset)** | 5  | 0      | 0       | Headset detect  | `bd2ae01791065c5d52524d44e3014e633617ea7a` |

## DEVICE FEATURES
| Feature                                                   | Feature                                                |
| --------------------------------------------------------- | ------------------------------------------------------ |
| android.hardware.audio.low_latency                        | android.hardware.sensor.stepdetector                   |
| android.hardware.audio.output                             | android.hardware.telephony                             |
| android.hardware.biometrics.face                          | android.hardware.telephony.gsm                         |
| android.hardware.bluetooth                                | android.hardware.telephony.ims                         |
| android.hardware.bluetooth_le                             | android.hardware.touchscreen                           |
| android.hardware.camera                                   | android.hardware.touchscreen.multitouch                |
| android.hardware.camera.any                               | android.hardware.touchscreen.multitouch.distinct       |
| android.hardware.camera.autofocus                         | android.hardware.touchscreen.multitouch.jazzhand       |
| android.hardware.camera.capability.manual_post_processing | android.hardware.usb.accessory                         |
| android.hardware.camera.capability.manual_sensor          | android.hardware.usb.host                              |
| android.hardware.camera.flash                             | android.hardware.vulkan.compute                        |
| android.hardware.camera.front                             | android.hardware.vulkan.level                          |
| android.hardware.camera.level.full                        | android.hardware.vulkan.version                        |
| android.hardware.faketouch                                | android.hardware.wifi                                  |
| android.hardware.fingerprint                              | android.hardware.wifi.direct                           |
| android.hardware.hardware_keystore                        | android.hardware.wifi.passpoint                        |
| android.hardware.location                                 | android.software.activities_on_secondary_displays      |
| android.hardware.location.gps                             | android.software.adoptable_storage                     |
| android.hardware.location.network                         | android.software.app_enumeration                       |
| android.hardware.microphone                               | android.software.app_widgets                           |
| android.hardware.opengles.aep                             | android.software.autofill                              |
| android.hardware.ram.normal                               | android.software.backup                                |
| android.hardware.screen.landscape                         | android.software.cant_save_state                       |
| android.hardware.screen.portrait                          | android.software.companion_device_setup                |
| android.hardware.security.model.compatible                | android.software.connectionservice                     |
| android.hardware.sensor.accelerometer                     | android.software.controls                              |
| android.hardware.sensor.light                             | android.software.cts                                   |
| android.hardware.sensor.proximity                         | android.software.device_admin                          |
| android.hardware.sensor.stepcounter                       | android.software.file_based_encryption                 |
| android.hardware.sensor.stepdetector                      | android.software.home_screen                           |
| android.hardware.telephony                                | android.software.incremental_delivery                  |
| android.hardware.telephony.gsm                            | android.software.input_methods                         |
| android.hardware.telephony.ims                            | android.software.ipsec_tunnels                         |
| android.hardware.touchscreen                              | android.software.live_wallpaper                        |
| android.hardware.touchscreen.multitouch                   | android.software.managed_users                         |
| android.hardware.touchscreen.multitouch.distinct          | android.software.midi                                  |
| android.hardware.touchscreen.multitouch.jazzhand          | android.software.picture_in_picture                    |
| android.hardware.usb.accessory                            | android.software.print                                 |
| android.hardware.usb.host                                 | android.software.secure_lock_screen                    |
| android.hardware.vulkan.compute                           | android.software.securely_removes_users                |
| android.hardware.vulkan.level                             | android.software.verified_boot                         |
| android.hardware.vulkan.version                           | android.software.voice_recognizers                     |
| android.hardware.wifi                                     | android.software.vulkan.deqp.level                     |
| android.hardware.wifi.direct                              | android.software.webview                               |
| android.hardware.wifi.passpoint                           | com.google.android.apps.dialer.SUPPORTED               |
| android.software.activities_on_secondary_displays         | com.google.android.feature.ASI                         |
| android.software.adoptable_storage                        | com.google.android.feature.D2D_CABLE_MIGRATION_FEATURE |
| android.software.app_enumeration                          | com.google.android.feature.PERSONAL_SAFETY             |
| android.software.app_widgets                              | com.google.android.feature.TURBO_PRELOAD               |
| android.software.autofill                                 | com.google.android.feature.WELLBEING                   |

## I2C:

| I²C Bus | Address | Device / Description |
| ------- | ------- | -------------------- |
| i2c-0   | 0x41    | chipone-tddi         |
| i2c-2   | 0x0c    | MAINAF               |
| i2c-2   | 0x10    | ccu_i2c_2_hwtrg      |
| i2c-2   | 0x1a    | kd_camera_hw         |
| i2c-2   | 0x50    | CAM_CAL_DRV          |
| i2c-3   | 0x34    | speaker_amp          |
| i2c-4   | 0x0c    | MAIN2AF              |
| i2c-4   | 0x11    | ccu_i2c_4_hwtrg      |
| i2c-4   | 0x2d    | kd_camera_hw_bus2    |
| i2c-4   | 0x3d    | kd_camera_hw_bus3    |
| i2c-4   | 0x50    | CAM_CAL_DEV3         |
| i2c-5   | 0x34    | mt6370_pmu           |
| i2c-5   | 0x4e    | usb_type_c           |
## SPI:

silead_fp_spi (spi0.0)

