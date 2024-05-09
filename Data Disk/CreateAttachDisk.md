Steps to Attach a Data Disk to a Virtual Machine in Azure:

    Sign in to Azure Portal:
        Open a web browser and navigate to the Azure Portal.
        Sign in using your Azure account credentials.

    Navigate to Virtual Machines:
        In the Azure Portal, click on "Virtual Machines" in the left-hand menu or search for "Virtual Machines" in the search bar.

    Select the Virtual Machine:
        Locate the virtual machine to which you want to attach a data disk from the list of VMs.
        Click on the VM to open its details.

    Navigate to Disks Settings:
        In the VM's overview pane, click on "Disks" under the Settings section.

    Attach a New Data Disk:
        In the Disks settings page, click on "+ Add data disk" at the top.

    Configure the Data Disk:
        Choose the settings for the new data disk:
            Name: Enter a name for the data disk.
            Disk Type: Select the type of disk (Standard HDD, Standard SSD, Premium SSD).
            Size (GiB): Specify the size of the data disk in gigabytes (GiB).
            LUN (Logical Unit Number): Leave this as auto-generated unless you have specific requirements.

    Review and Save Changes:
        After configuring the data disk settings, click "Save" to attach the new data disk to the virtual machine.

    Connect to the Virtual Machine:
        Once the data disk is attached, you can connect to the virtual machine using Remote Desktop Protocol (RDP) or SSH (for Linux VMs) to manage the disk.

    Initialize and Format the Data Disk (if required):
        After connecting to the VM, if the data disk is not automatically recognized, you may need to initialize and format the disk within the operating system.
        For Windows VMs, open Disk Management to initialize and format the disk.
        For Linux VMs, use commands like fdisk and mkfs to partition and format the disk.
