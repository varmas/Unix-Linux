BOOT  / POWER ON 
----------------

SWITCH ON

	CPU INIT

	Addressing mode set (32/64)

	ROM BIOS lookup

		INIT BIOS

BIOS

	H/W TESTS and CMOS RAM tests

	POST

	Detects & Test H/W & Init H/W 

	Back to CPU init as well

	Find BOOT DEVICE

		Execute MBR

MasterBootRecord

	Find BOOT MGR

BOOT MGR (LILO/GRUB/BOOT 0)

	FIND Filesystem

	WHERE's BOOT WHERE's SWAP ?

		Execute Kernel

KERNEL

	INIT RD / RAM DISK

	/ROOT

		Execute /SBIN/INIT

INIT

	INIT TAB – 
	
Execute RUN LEVEL programs

START UP SCRIPTS (/etc/init.d/ or etc/rc.d/ )

DONE

	BASH SHELL AFTER LOGON
