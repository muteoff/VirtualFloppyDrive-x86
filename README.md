# VirtualFloppyDrive
This is a virtual floppy drive for Windows NT / 2000 / XP(reported to work also on 2003 Server and Vista) originally developed by **Ken Kato**([English](https://web.archive.org/web/20100902032534/http://chitchat.at.infoseek.co.jp/vmware/vfd.html), [Japanese](https://web.archive.org/web/20100726144620/http://chitchat.at.infoseek.co.jp/vmware/vfdj.html)) from 2003 to 2008 and uploaded here by me to only fix one annoying bug in the Media Type drop-down list(combo box):

<p align="center">
  <img src="https://user-images.githubusercontent.com/25485348/176880353-66cfa339-e0a0-4a78-9992-1bee56019871.png" alt="Reason">
</p>

You can mount a floppy image file as a virtual floppy drive and directly access the contents — view, edit, rename, delete or create files on a virtual floppy, format a virtual floppy, launch a program on a virtual floppy... almost anything you can do with a real floppy.

## Features
- 2 virtual floppy drives.

- FILE mode and RAM mode
In FILE mode, image files are mounted directly.
Changes made in virtual media are written to the file immediately.
In RAM mode, on memory copy of image files are mounted.
Enables to open read-only files as writable media.
Changes are not written back to the image file (discarded on image close).

- Supports the following media types:
160KB (5.25"), 180KB (5.25"), 320KB (5.25"), 360KB (5.25"), 640KB (5.25"/3.5"), 720KB (5.25"/3.5"), 820KB (3.5"), 1.2MB (5.25"/3.5"), 1.44MB (3.5"), 1.68MB (3.5"), 1.72MB (3.5"), 2.88MB (3.5").

- WinImage compressed image (*.IMZ) support.
RAM mode open only, and cannot save into an IMZ file.

- Formatting virtual media
New images created with VFD are pre-formatted with FAT12.
Enables to format media which Windows' format cannot handle.

- Switching write-protection of virtual media on the fly.

- Persistent drive letters
A drive letter is not removed when an image is closed.
Drive letters are preserved until explicitly removed.
The same drive letter is assigned the next time the driver starts.
On Windows 2000 SP2 and later, drive letters are not deleted when the user logged off.
On Windows XP and Terminal Servers drive letters are globally visible.
You can choose between the old (ephemeral) drive letters.

- Shell extension
Open/Close an image with the right click menu on the virtual drive icon.
Virtual Floppy Drive property sheet.
Drag-and-drop an image file with the right button to the virtual drive icon to open it (Windows 2000 and later).
