PHP CSS Compressor
==============

Compresses an array of CSS files into one. 

###How it works

- If no compressed file exist, it creates one
- If the compressed file is older than one of the original files in creates a new compressed file
- If the compressed file is newer than the original files, it simply deliveres the compressed file

###How to use it
Configure the variables:
- $css_cache_file (The full path to where you want to store you compressed CSS)
- $css_path (The full path to your original CSS files)
- $css_files (An array of your CSS files, the filenames)

Include csscompressor.php as a CSS file in your HTML document.
