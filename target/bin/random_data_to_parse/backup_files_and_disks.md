# BACKUP FILES AND DISKS

## disks

```
- no need for a value
```

```
? todo
```

| id  | location       | label                | color      | size  | brand           | filesystem | all  | free | port  | usb version |
|-----|----------------|----------------------|------------|-------|-----------------|------------|------|------|-------|-------------|
| 1   | p_fikirtepe    | l_fikirtepe_big      | black      | big   | western_digital | exfat      | 1000 | 500+ | A     | ?           |
| 18  | p_fikirtepe    | l_fikirtepe_small    | black      | small | sandisk         | exfat      |      |      | A & C | 3.2         |
| 6   | p_fikirtepe    | l_fikirtepe_formattr | black&red  | small | sandisk         | -          | 30   | -    | A     | ?           |
| 7   | p_aktas        | l_aktas_big          | black      | big   | western_digital | exfat      | 300  | 280  | A     | ?           |
| 12  | p_aktas        | l_aktas_small        | black      | small | sandisk         | exfat      |      |      | A & C | 3.2         |
| 2   | p_aktas        | l_aktas_formattr     | black      | small | kingston        | -          | 30   | -    | A     | ?           |
| 5   | p_island       | l_island_big         | black      | big   | western_digital | ntfs       | 930  | 500+ | A     | ?           |
| 11  | p_island       | l_island_small       | white      | small | seagate         | exfat      | 123  | 90   | A     | 3           |
| 19  | p_island       | l_island_formattr    | white      | small | kingston        | -          | 120  | -    | A     | 3           |
| 14  | p_dogs         | l_dogs               | gold       | small | verbatim        | exfat      | 61   | ?    | A     | 3           |
| 10  | p_cengz        | l_cengz              | grey       | small | sandisk         | exfat      | 250  | 166  | ?     | ?           |
| 15  | p_is_bank      | l_is_bank            | black      | small | sandisk         | exfat      | 128  | 91   | A     | 3.2         |
| 16  | p_garanti_pndk | l_garanti_pndk       | black      | small | sandisk         | exfat      | 64   | 29   | A     | 3.2         |
| 104 | -              | l_android_samsug     | green/grey | -     | samsung         | -          | -    | -    | C     | -           |
| 102 | -              | l_hp_laptop_hdd      | -          | -     | -               | ex4        | 1000 | all  | -     | -           |
| 101 | -              | l_hp_laptop_ssd      | -          | -     | -               | ex4        | 250  | all  | -     | -           |
| 110 | -              | l_lenovo_laptop      | -          | -     | -               | ex4        | 1000 | 500+ | -     | -           |
| 100 | -              | l_g_clud             | -          | -     | -               | -          | 15   | 13   | -     | -           |
| 103 | -              | l_y_clud             | -          | -     | -               | -          | 10   | 8    | -     | -           |
| 106 | -              | l_m_clud             | -          | -     | -               | -          | 5    | 3    | -     | -           |
| 105 | -              | l_g_clud_selim       | -          | -     | -               | -          | -    | -    | -     | -           |

## empty disks

| id | location    | label | color       | size  | brand | filesystem | all | free | port | usb version |
|----|-------------|-------|-------------|-------|-------|------------|-----|------|------|-------------|
| 4  | p_island    | -     | white       | small | tav   | exfat      | 15  | -    | A    | ?           |
| 8  | p_fikirtepe | -     | white&black | small | vmi   | exfat      | 4   | -    | A    | ?           |

## relations

| directories           | big             | small             | yabancı          | clud     | l_g_clud_selim |
|-----------------------|-----------------|-------------------|------------------|----------|----------------|
| STORAGE               | l_aktas_big     | l_aktas_small     | l_is_bank        | l_m_clud |                |
| STORAGE               | l_island_big    | l_island_small    | l_dogs           | l_y_clud |                |
| STORAGE               | l_fikirtepe_big | l_fikirtepe_small | l_cengz          | l_g_clud |                |
| STORAGE               |                 |                   | l_garanti_pndk   |          |                |
| STORAGE               |                 |                   | l_android_samsug |          |                |
| STORAGE               |                 |                   |                  |          |                |
| VM                    | *               |                   |                  |          |                |
| ISO                   | *               |                   |                  |          |                |
| APPS                  | *               |                   |                  |          |                |
| TEMP                  |                 | *                 |                  |          |                |
| PUBLIC                |                 | *                 |                  |          |                |
| APPS CRITICAL         |                 | *                 | *                |          |                |
| MUSIC                 |                 | *                 | *                |          |                |
| CODE EXAMPLES         |                 | *                 | *                |          |                |
| DANCE LESSON          |                 | *                 | *                | *        |                |
| VIDEOS_1              |                 | *                 | *                | *        | *              |
| BOOKS                 |                 | *                 | *                | *        | *              |
| FAMILY                |                 | *                 | *                | *        | *              |
| RIPPLE                |                 | *                 | *                | *        | *              |
| PHOTOS_1              |                 | *                 | *                | *        | *              |
| PHOTOS_PROFILE        |                 | *                 | *                | *        | *              |
| FILES_MIX_UPDATE_FAST |                 | *                 | *                | *        | *              |
| FILES_MIX_FIXED       |                 | *                 | *                | *        | *              |

- Formatters has only bootable Fedora.

- l_lenovo_laptop has all.

## Root directory

Add this empty file to all partitions:

> INFO__no_99__type_A__brand__external__color__size__format__usb_v3__any_keyword_other

Add this only to important disks:

> INFO__BENI_OKU___READ_ME.txt
