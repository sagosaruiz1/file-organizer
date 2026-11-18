
# File Organizer
 
A small Python script that sorts the files in a folder into subfolders by file type.
 
## Requirements
 
- Python 3.6+
- No extra packages needed
## How to Use
 
1. Save the script as `organize_files.py`.
2. Run it:
```bash
python organize_files.py
```
 
3. Enter the path of the folder you want to organize when asked:
```
Enter the directory path to organize: /Users/yourname/Downloads
```
 
## Folders Created
 
- `Images`: .jpg, .jpeg, .png, .gif, .bmp, .tiff
- `Videos`: .mp4, .mkv, .flv, .avi, .mov
- `Documents`: .pdf, .doc, .docx, .txt, .ppt, .pptx, .xls, .xlsx
- `Audio`: .mp3, .wav, .aac, .flac
- `Data`: .csv, .json, .xml
- `Others`: everything else
To change the categories, edit `FILE_CATEGORIES` at the top of the script.
 
## Notes
 
- Files are **moved**, not copied, and there is no undo. Back up important folders first.
- Only files directly inside the folder are organized. Existing subfolders are skipped.
 
