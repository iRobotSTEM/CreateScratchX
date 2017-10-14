iRobot Create Scratch Offline Setup Instructions:

1) Install python (2.7.X)
 - Windows 32 bit version: https://www.python.org/ftp/python/2.7.14/python-2.7.14.msi
2) Install python windows extensions (for python 2.7.X)
- Windows 32 bit version: https://pypi.python.org/packages/91/87/2ed2b036a2dd9037074ba5862ff959e9541b9625f3ae8c90b8bacd38589b/pypiwin32-219.win32-py2.7.exe#md5=bb89d94a26197a467b27f9de2b24a344
3) Install pyserial (for python 2.7.X; Used for communicating with the Create using python)
- Windows installer: https://pypi.python.org/packages/47/c9/7802e11ab388ad1539de716649add8bb8ca8bdff660364b3a404f79c27b7/pyserial-2.7.win32.exe#md5=21555387937eeb79126cde25abee4b35
4) Install the latest adobe flash:
- https://get.adobe.com/flashplayer/otherversions/
5) Make sure to have the ESR version of firefox (this is the only browser that works with Scratch)
- Find  installer here: https://www.mozilla.org/en-US/firefox/organizations/all/
6) Install Scratch Extension Plugin for Windows (other browser):
- https://scratch.mit.edu/info/ext_download/
7) Make a "Create-Scratch" folder (on desktop or in Documents)
8) Download Scratch
- https://github.com/LLK/scratchx/archive/gh-pages.zip
9) Extract Scratch into the "Create-Scratch" folder
10) Download the Create Scratch extension into "Create-Scratch/scratchx-gh-pages/scratchx-gh-pages/"
- Download https://raw.githubusercontent.com/iRobotSTEM/CreateScratchX/gh-pages/roomba600Extension.js
11) Download and copy helper scripts into "Create-Scratch"
- https://github.com/iRobotSTEM/CreateScratchX/raw/gh-pages/Create%20Scratch%20offline%20helpers.zip


How to run Create Scratch (after setup):
1) Navigate to the "Create-Scratch" folder created during setup
1) Run "run_scratch.bat" (and leave open)
2) Do either A or B below:
   A) Open "Create Scratchx" internet shortcut in the Firefox ESR browser (installed in setup step 5)
   B) Open Firefox ESR broswer and go to: "http://localhost:8000/?url=http://localhost:8000/roomba600Extension.js"
