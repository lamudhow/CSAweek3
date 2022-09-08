# CSAweek3
EIT CSA Week3 Lab
Michael Brader 2022003459

# Install Windows 7 and Zorin Linux

## Installing Windows 7

* Insert the Windows 7 image USB stick
* Start the computer (if necessary, enter the BIOS and configure the machine to boot from USB)
* When the [Language selection screen](win7lang.png) appears, select appropriate values
* Do similar for time zone, currency format etc., then click '[Install Windows 7](win7install.png)'
* Choose [Custom Install, not Upgrade](win7custom.png) to ensure that a fresh installation is performed
* Choose a setting for [security updates](win78protect.png)
* The [install should finish](win7instend.png) and then the computer should restart
* After the restart you will be prompted for a [host and username/password](win7user.png), then a [product key](win7prodkey.png) (the product key can be skipped)
* Finally you will be asked to [set time and date](win7timedate.png)
* At this stage, Windows 7 is installed

## Installing Zorin Linux

* Your first step is to shrink the size of the Windows partition to make room for Zorin Linux. The installer can do this for you, but it is always best to resize Windows partitions inside Windows
* In Windows 7, hold down 'Win + r' to select the run command dialog box
* Enter ['diskmgmt.msc' and type return](win7diskmgmt.png)
* In the [disk management tool](win7part1.png), right-click on the C: partition and select ['Shrink Volume'](win7part2.png)
* Shrink the C: partition to allocate space for Zorin Linux. [50GB is recommended, it must be at least 20GB](win7shrinksize.png)
* Save changes, quit the tool and shutdown the machine
* Insert the Zorin Linux USB stick and start the computer
* When the machine boots you should see an option to [Try or Install Zorin Linux](zorintry.png). Choose ['Install'](zorininstall.png)
* You will be given options to install Zorin on the whole hard drive, or alongside Windows 7. Choose ['alongside'](zorinalongside.png)
* You will be asked to set the timezone.
* The installation should proceed at this point and when it is complete you will [receive a confirmation](zorincomplete.png)
* Installation of Zorin Linux is now complete

## Choosing operating system at boot time

When you restart the computer, after the diagnostics you will enter [a tool named Grub](zoringrub.png). At this point you can select using arrow keys and Enter whether to boot into Windows 7 or Zorin

