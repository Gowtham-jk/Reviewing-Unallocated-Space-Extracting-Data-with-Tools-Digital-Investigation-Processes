# Reviewing-Unallocated-Space-Extracting-Data-with-Tools-Digital-Investigation-Processes
## AIM:
To review unallocated space in a disk image, extract data using forensic tools, and understand the digital investigation process.

## DESIGN STEPS:
### Step 1:
Use tools like Autopsy or Sleuth Kit (blkls, icat) to identify and analyze unallocated space.

### Step 2:
Extract data from unallocated space and examine for hidden or deleted content.

### Step 3:
Document and interpret findings as part of the digital investigation process.

## PROGRAM:
Data Extraction and Investigation Tool Usage
```bash
lsblk
```

```bash
sudo dd if=/dev/sda of=/home/kali/disk.img bs=512
```

```bash
mmls ~/disk.img
```
```bash
sudo ls -lh disk.img
```
```bash
strings disk.img | less

```

## OUTPUT:
![Screenshot 2025-04-27 213442](https://github.com/user-attachments/assets/bb0e027b-ba4e-4aec-bc8a-b0f8a0e69aeb)
![Screenshot 2025-04-27 213453](https://github.com/user-attachments/assets/3ab90b04-47b0-41d6-ab1d-d8d24282c6a4)
![Screenshot 2025-04-27 213522](https://github.com/user-attachments/assets/f89b563e-a639-4ec3-bcc6-f06a8cf35019)
![Screenshot 2025-04-27 213505](https://github.com/user-attachments/assets/d2118de2-0b82-48ab-8ec4-98350a480f83)
![Screenshot 2025-04-27 213607](https://github.com/user-attachments/assets/57ac4993-05e3-443c-b926-b79e54352736)



## RESULT:
The unallocated space was successfully analyzed, data was extracted, and the digital investigation process was followed effectively.
