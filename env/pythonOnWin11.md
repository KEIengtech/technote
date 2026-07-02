~~~
관리자 모드로 윈도우 파워쉘 열고, 미니콘다 설치
> winget install --id CondaForge.Miniforge3 -e 
미니콘다 설치 경로 초기화
> & "C:\ProgramData\miniforge3\Scripts\conda.exe" init powershell

관리자 모드로 윈도우 파워쉘 열고,
conda create -n new python=3.12

(base) PS D:\python> conda env list

# conda environments:
#
# * -> active
# + -> frozen
base                 *   C:\ProgramData\miniforge3
green                    C:\ProgramData\miniforge3\envs\green

(base) PS D:\python> conda activate green
(green) PS D:\python> deactivate
(green) PS D:\python>
~~~
