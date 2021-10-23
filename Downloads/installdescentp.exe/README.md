# installdescent.exe
This file was originally available at <http://www.gamesonline.com/files/installdescentp.exe>.

## How to extract
It wouldn’t let me finish the installation because I didn’t have Descent Online installed, but I was still able to access some data stored in this file.

1. Extract the WinZip Self-Extractor.
	1. Run installdescentp.exe.
	2. Click “Setup”.
	3. This will open an InstallShield wizard.
	4. Keep the installer open, and go to `C:\users\<your username>\Temp`.
	5. Make a copy of the files in that directory.
	6. Close out of the installation wizard.
	7. Close out of the WinZip Self-Extractor.
2. Extract files from the InstallShield wizard.
	1. Go to the copy you made earlier. There’s several files here that can be examined. The ones that I found to be the most interesting are the InstallShield Z Archives.
	2. Find any InstallShiled Z Archives. Look for files that end in `.z` or `.lib`. TIP: [file](https://darwinsys.com/file/) can identify InstallShield Z Archives. Run `file ./*`.
	3. Download the InstallShield File Compressor. You can find a copy [here](https://archive.org/details/InstallShieldTools).
	4. Run `MKDIR output`
	5. Run `ICOMP <archive> output\ -d -i`

## Metadata
|Filename                   |Description                         |Version            |Date             | Size      |
|---------------------------|------------------------------------|-------------------|-----------------|-----------|
|_Descent Online (upgrade)_ |Patch file from 0.85 to 0.84.       |0.85 to 0.84       |April 15th, 1997 |1.4 Megs   |
|_Descent Online (upgrade)_ |Patch file from 1.06.00 to 1.07.00. |1.06.00 to 1.07.00 |June 11, 1997    |1.4 Megs   |
