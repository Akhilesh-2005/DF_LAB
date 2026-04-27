Forensic Disk Imaging and Integrity Verification (SHA-256)
Aim:
To create a forensic disk image using FTK Imager and Guymager.
To verify the integrity of the acquired image using SHA-256 hashing.

Theory:
Forensic disk imaging is the process of creating an exact bit-by-bit copy of a storage device without altering the original data.
Tools like FTK Imager and Guymager are used to ensure a forensically sound acquisition.
SHA-256 hashing is applied to both original and acquired images to verify data integrity and ensure no modification has occurred.

Procedure:
Using FTK Imager (Windows):
Install and open FTK Imager.
Click on File → Create Disk Image.
Select source type (e.g., Physical Drive / Logical Drive).
Choose the target drive to image.
Select image type (E01 recommended).
Enter case details (optional but recommended).
Choose destination folder and file name.
Enable Verify images after acquisition.
Start the imaging process.
Note the generated SHA-256 hash value.

Using Guymager (Linux):
Open terminal and run Guymager as root.
Select the target storage device.
Right-click and choose Acquire Image.
Select image format (EWF or RAW).
Choose destination directory.
Enable Hash calculation (SHA-256).
Start acquisition process.
Wait for imaging and hashing to complete.
Note the displayed SHA-256 hash values.
Hash Verification
Compare the SHA-256 hash of the original device and the acquired image.
Ensure both hash values match exactly.
Matching hashes confirm integrity and authenticity of the image.

Result:
A forensic disk image was successfully created using FTK Imager and Guymager.
The SHA-256 hash values matched, confirming the integrity of the acquired image.

Download Link:
[Open FTK Imager](https://www.exterro.com/ftk-downloads/ftk-imager-pro-8-2-0-26)
