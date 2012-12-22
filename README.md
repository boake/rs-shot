# Resave shot
Simple tool to resave multiple bloated mplayer2 screenshots. Requires GIMP. Most likely only works on Linux with Ruby.

## Use
Move rs-shot to a location in your $PATH. Simply run rs-shot in the directory with your bloated files.

## Other
This can easily be modified and used for other wrongfully bloated files. You simply change `bloat_size = 2774103` to `bloat_size = some_bloat_size_in_bytes` and `file_prefix = "shot"` to `file_prefix = "other_default_prefix"`. You may leave the file prefix blank if there is no prefix e.g. `file_prefix = ""`. **Note: leaving the file prefix blank will resave all files in the directory.**


To be clear, this does not resize the actual image file size it simply corrects it by resaving with GIMP.