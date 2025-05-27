# Useful Jupyter Notebooks
Collection of useful Jupyter Notebooks

## A. Smart DownLoader

✨ Features:
### 1. Clean tqdm Progress Bar
* NO MORE old "Progress: X%" messages
* Beautiful tqdm progress bar: Creating archive: 45%|████▌ | 1234/2750 [00:30<00:42, 35.2items/s]
* Shows current file/directory being processed

### 2. Comprehensive Exclusion Tracking
* Counts omitted files and directories separately
* Calculates total size of excluded content
* Shows space savings from exclusions

### 3. Enhanced Reporting
* 📊 __Summary:__
  * Items processed: 8,459
  * Items excluded: 1,279
  * Archive size: 450.3 MB
  * Original size: 2.1 GB
  * Compression ratio: 78.6%
  * Space saved by exclusions: 1.2 GB
  * Errors encountered: 0
  
### 4. Two-Pass Architecture
* First pass: Scans and categorizes all items
* Second pass: Creates archive with accurate progress tracking

### 5. Better Error Handling
* Uses tqdm.write() for errors so they don't interfere with progress bar
* Comprehensive error reporting at the end

### 6. 🚀 To Use:
* Update the ROOT_DIRECTORY to your target path
* Update the EXCLUDE_PATTERNS if any (inlcuding folders)
* Update the OUTPUT_ARCHIVE if you need a different folder name
* Run all cells in order
* Execute the archiving cell

### 7. This implementation gives you:
* Real-time visual progress bar
* Current processing speed
* Time elapsed and estimated remaining
* Current file being processed
* Detailed statistics about what was included vs excluded

This should solve all the issues you were experiencing!
