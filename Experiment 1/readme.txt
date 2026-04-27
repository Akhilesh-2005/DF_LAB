Aim:
To create a forensic disk image using FTK Imager and Guymager.
To verify the integrity of the acquired image using SHA-256 hashing.

Theory:
A forensic disk image is a bit-by-bit copy of a storage device that preserves all data, including deleted and hidden files.
Tools like FTK Imager and Guymager are used to acquire such images without altering the original evidence.
SHA-256 hashing is used to ensure integrity by generating a unique hash value for both original and imaged data for comparison.

Procedure:
Launch FTK Imager or Guymager on the system.
Connect the target storage device (USB/HDD).
Select the option to create a disk image.
Choose the source drive (physical drive or logical partition).
Select image format (E01 or RAW).
Enter case details (case number, examiner name, description).
Choose destination path to save the image file.
Enable hash calculation (select SHA-256).
Start the imaging process.
Wait until imaging is completed successfully.
Note the generated SHA-256 hash value of the original data.
Verify the image by comparing the hash of the created image file.
Confirm that both hash values match to ensure integrity.

Result:
The forensic disk image was successfully created using FTK Imager and Guymager.
The SHA-256 hash values of the original and imaged data matched, confirming data integrity and authenticity.

Download Link:
[Open FTK Imager](https://www.exterro.com/ftk-downloads/ftk-imager-pro-8-2-0-26)
