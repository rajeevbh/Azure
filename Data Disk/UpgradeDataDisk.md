Steps to Increase the Size of a Data Drive (Data Disk) in Azure:

    Sign in to Azure Portal:
        Open a web browser and navigate to the Azure Portal.
        Sign in using your Azure account credentials.

    Navigate to Virtual Machines:
        In the Azure Portal, click on "Virtual Machines" in the left-hand menu or search for "Virtual Machines" in the search bar.

    Select the Virtual Machine with Attached Data Disk:
        Locate the virtual machine that has the data disk you want to resize from the list of VMs.
        Click on the VM to open its details.

    Identify the Data Disk to Resize:
        In the VM's overview pane, click on "Disks" under the Settings section.
        Note down the name of the data disk that you want to resize (e.g., mydatadisk).

    Stop the Virtual Machine (if required):
        If the VM is running, you may need to stop it before resizing the data disk.
        In the VM's overview pane, click on "Stop" to deallocate the VM.

    Resize the Data Disk:
        In the Azure Portal, navigate to "Disks" in the left-hand menu or search for "Disks" in the search bar.

    Select the Data Disk for Resizing:
        Locate the data disk you want to resize from the list of disks.
        Click on the data disk to open its details.

    Resize the Data Disk: (Before that stop and dettach the disk)
        In the data disk details pane, click on "Resize" at the top.
        Enter the new size (in gigabytes - GiB) for the data disk.
        Click "Save" to apply the new size.

    Start the Virtual Machine:
        After resizing the data disk, go back to the VM's overview pane.
        Click on "Start" to start the VM (if it was stopped).

    Extend the File System (if required):
        After the VM is running, connect to the VM using Remote Desktop Protocol (RDP) or SSH (for Linux VMs).
        Open Disk Management (for Windows) or use command-line tools (e.g., fdisk, resize2fs for Linux) to extend the file system to use the additional disk space.
