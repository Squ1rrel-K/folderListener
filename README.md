## About python_folder_listener

python_folder_listener is a folder listener writen by python, which monitors file movement event in one specific folder
constantly and writes such information into an Excel file.

## How to use

1. Build proper Python environment
2. Download libraries: watchdog, openpyxl
3. Custom your own [excel_path], [folder_path_tem], [folder_path] values ( line 11, 12 , 13 )
4. Open python_folder_listener in IDE or run "py main.py" in console
5. As python_folder_listener is opened, file created and deleted events will be detected automatically, which modifies the
   Excel file

## Modify for private use

Custom method work_on_excel_by_event_created() 

## Future plan 

Log system
better input by IO console 

