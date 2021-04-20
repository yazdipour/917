# 917 Program

## Instalation

- Download the latest VHD files from <https://github.com/yazdipour/917/releases>
- Use RUFUS to write VHD on your storage device

## Configuration

To change VHD content, open `Disk Management` and click `Action > Attach VHD` to mount the VHD file as a hard drive.

After changing VHD content, you should unmount it from Disk Managment window and it will be ready to use.

### AUTOEXEC.BAT

This is already predefined in VHD files. 

But if you want to change it:

- To run without Machine `cu m1 d2`
- To run on a Machine `cu w d0 g1 m1`
- `d1` is for print-on, `d0` print-off

## How did i make it work

Using three MSDOS 6.2 img files, I was able to create a MSDOS virtual environment in VirtualBox.
After that I used the same VHD file and attached it to my system, copied all the 917 files (except `DOS folder, COMMAND.EXE, IO.SYS, MSDOS.SYS`).