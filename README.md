# numeric-system-converter

### Usage: ###

   ```
   usage: convert_numsys.py [-h] {dec,bin,hex,oct} {dec,bin,hex,oct} value
   
   Basic positional numeral system converter
   
   positional arguments:
     {dec,bin,hex,oct}  Input numeral system (format: dec, bin, hex, oct)
     {dec,bin,hex,oct}  Output numeral system (format: dec, bin, hex, oct)
     value              Value to be converted
   
   options:
     -h, --help         show this help message and exit
   ```

### Example: ###

   ```
   python convert_numsys.py dec bin 17223
   ```

   This command executes the python script with the positional arguments for decimal to binary conversion. Note: The last positional argument must be a number of the given input type (In this case decimal).

   > Argument 1 -> input "dec" (decimal)

   > Argument 2 -> output "bin" (binary)

   > Argument 3 -> value "17223"

### Help: ###

   ```
   python convert_numsys.py -h
   ```
   Or
   ```
   python convert_numsys.py --help
   ```

   This command prints the argparse help information to the executing console interface.

   > More information about argparse here https://docs.python.org/3/library/argparse.html#
