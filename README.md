# RuneCrypt
CURRENTLY SCHEDULED FOR REWRITE <br>
A hardcore encryption application - Currently in beta testing<br>

# Basic Usage:<br>
To install the necessary libraries use-<br>
 python3 autoinstaller.py <br>
 
Most used commands-<br>
  python3 RuneCrypt.py -f some_file_name_or_path -decoy t<br>
  python3 RuneCrypt.py -f rune.glyph -d crypto.glyph<br>
  
To use the default action of encrypting a file with 15 random layers-<br>
  python3 RuneCrypt.py -f some_file_name_or_path<br>
  
To decrypt a rune.glyph-<br>
  python3 RuneCrypt.py -f rune.glyph -d crypto.glyph<br>
  
To specify encryption layers-<br>
  python3 RuneCrypt.py -f some_file_name_or_path -e random-random-random etc.<br>
  
To use the streamline glyph ability-<br>
  python3 RuneCrypt.py -f some_file_name_or_path -g glyph.json<br>
  
To create a rune.glyph decoy-<br>
  python3 RuneCrypt.py -f some_file_name_or_path -decoy t<br>
