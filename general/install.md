# 윈도우11에서 SW설치
## scoop 설치
- 관리자 권한으로 쉘 열기
- iex "& {$(irm get.scoop.sh)} -RunAsAdmin"
~~~
PS C:\Users\KEI> iex "& {$(irm get.scoop.sh)} -RunAsAdmin"
Initializing...
Downloading...
Extracting...
Creating shim...
Adding ~\scoop\shims to your path.
Scoop was installed successfully!
Type 'scoop help' for instructions.
PS C:\Users\KEI> scoop install nodejs
~~~
### node 설치
- scoop install nodejs
~~~
PS C:\Users\KEI> scoop install nodejs
Installing '7zip' (26.01) [64bit] from 'main' bucket
7z2601-x64.msi (1.9 MB) [=====================================================================================] 100%
Checking hash of 7z2601-x64.msi ... ok.
Extracting 7z2601-x64.msi ... done.
Linking ~\scoop\apps\7zip\current => ~\scoop\apps\7zip\26.01
Creating shim for '7z'.
Creating shim for '7zG'.
Making C:\Users\KEI\scoop\shims\7zg.exe a GUI binary.
Creating shim for '7zFM'.
Making C:\Users\KEI\scoop\shims\7zfm.exe a GUI binary.
Creating shortcut for 7-Zip\7-Zip File Manager (7zFM.exe)
Creating shortcut for 7-Zip\7-Zip Help (7-zip.chm)
Persisting Codecs
Persisting Formats
Running post_install script...done.
'7zip' (26.01) was installed successfully!
Notes
-----
To register the context menu entry, please execute the following command:
reg import "C:\Users\KEI\scoop\apps\7zip\current\install-context.reg"

If an error occurs while attempting to delete files during uninstallation, run the following command and then retry:
Stop-Process -Name 'explorer'
Installing 'nodejs' (26.3.0) [64bit] from 'main' bucket
node-v26.3.0-win-x64.7z (24.5 MB) [===========================================================================] 100%
Checking hash of node-v26.3.0-win-x64.7z ... ok.
Extracting node-v26.3.0-win-x64.7z ... done.
Linking ~\scoop\apps\nodejs\current => ~\scoop\apps\nodejs\26.3.0
Adding ~\scoop\apps\nodejs\current\bin to your path.
Adding ~\scoop\apps\nodejs\current to your path.
Persisting bin
Persisting cache
Running post_install script...done.
'nodejs' (26.3.0) was installed successfully!
PS C:\Users\KEI> node -v
v26.3.0
~~~
