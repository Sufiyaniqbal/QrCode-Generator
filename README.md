# QrCode-Generator
1 . Set Up Enviornment
	1 . Install Python (if not installed) from python.org.
	2 . Create a project folder
	3 . Open terminal or command prompt and go to that folder:
	4 . Create a virtual environment:
			  python -m venv qr_code_project
	5 . Activate the virtual environment:
			  qr_code_project\Scripts\activate
     
2 . Install Required Packages
  1 . pip install fastapi uvicorn pillow qrcode

3 . Write Code
    main.py - This actual page , where the code added.

4 . Run the code
  1 . Manually
    uvicorn main:app --reload
  2 . Using start.bat - need to click
    @echo off
    cd /d %~dp0
    call qr_code_project\Scripts\activate
    uvicorn main:app --host 127.0.0.1 --port 8000
  3 . Window startup Page ( it will work automatically )
    Create a batch file
    Create a task and connect to batch file


