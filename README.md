`for ext in docx docm dot dotm pptx pptm xls xlsm exe ps1 7z zip rar; do dd if=/dev/random of=random_data.$ext bs=512KB count=1; done`
