- cmd 환경에서 설치 후 새 cmd에서 확인
~~~
D:\>agy --version
1.1.27

D:\>
~~~
- cmd 환경에서 설치
~~~
D:\>curl -fsSL https://antigravity.google/install.sh | bash
'bash'은(는) 내부 또는 외부 명령, 실행할 수 있는 프로그램, 또는
배치 파일이 아닙니다.

D:\>curl -fsSL https://antigravity.google/cli/install.cmd -o install.cmd && install.cmd && del install.cmd
ERROR: logging before google.Init: I0907 13:54:58.275040       1 installer.go:27] Running Antigravity CLI setup...
ERROR: logging before google.Init: I0907 13:54:58.348060       1 installer_windows.go:45] Configuring Windows user PATH registry environment...
ERROR: logging before google.Init: I0907 13:54:58.348060       1 installer_windows.go:117] Successfully added %LOCALAPPDATA%\agy\bin to User PATH registry variable.
ERROR: logging before google.Init: I0907 13:54:58.348573       1 installer_windows.go:148] Broadcasting environment update system-wide...
ERROR: logging before google.Init: I0907 13:54:59.326189       1 installer_windows.go:167] Environment update broadcast completed.

Warning: C:\Users\KEI\AppData\Local\agy\bin is not present in your active Environment PATH.
Please restart your active terminal session, or add it manually if needed.


✅ Antigravity CLI binary placed successfully at C:\Users\a\AppData\Local\agy\bin\agy.exe
Note: The binary is installed, but it is not in your active PATH. Please follow the instructions above to add it, then restart your terminal session.
~~~
