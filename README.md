# txt2CANTVMAC

A tool for converting strings, which are in *.txt file, into binary file.

## How To

Just enter the following command in Linux.

    ./txt2CANTVMAC.py *.txt

or

    python txt2CANTVMAC.py *.txt

For example, there is a \*.txt file whose name is **U65\_MAC\_address.txt**. Its content as follow,

	A8:82:7F:00:59:CE
	A8:82:7F:00:59:CF

After entering command `./txt2CANTVMAC.py U65_MAC_address.txt`, there will be two \*.bin files, **MAC\_a8827f0059ce.bin** and **MAC\_a8827f0059cf.bin**, are generated in **MAC** folder. These two \*.bin files are what we want.