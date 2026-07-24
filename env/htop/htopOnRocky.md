

~~~
$ cat /etc/os-release
NAME="Rocky Linux"
VERSION="8.10 (Green Obsidian)"
ID="rocky"
ID_LIKE="rhel centos fedora"
VERSION_ID="8.10"
PLATFORM_ID="platform:el8"
PRETTY_NAME="Rocky Linux 8.10 (Green Obsidian)"
ANSI_COLOR="0;32"
LOGO="fedora-logo-icon"
CPE_NAME="cpe:/o:rocky:rocky:8:GA"
HOME_URL="https://rockylinux.org/"
BUG_REPORT_URL="https://bugs.rockylinux.org/"
SUPPORT_END="2029-05-31"
ROCKY_SUPPORT_PRODUCT="Rocky-Linux-8"
ROCKY_SUPPORT_PRODUCT_VERSION="8.10"
REDHAT_SUPPORT_PRODUCT="Rocky Linux"
REDHAT_SUPPORT_PRODUCT_VERSION="8.10"
~~~
~~~
$ sudo dnf install -y epel-release
마지막 메타자료 만료확인(1:37:10 이전): 2026년 07월 24일 (금) 오후 09시 04분 00초.
종속성이 해결되었습니다.
========================================================================================================================
 꾸러미                          구조                      버전                         저장소                     크기
========================================================================================================================
설치 중:
 epel-release                    noarch                    8-22.el8                     extras                     25 k

연결 요약
========================================================================================================================
설치  1 꾸러미

전체 내려받기 크기: 25 k
설치된 크기 : 34 k
꾸러미 내려받기 중:
epel-release-8-22.el8.noarch.rpm                                                        159 kB/s |  25 kB     00:00
------------------------------------------------------------------------------------------------------------------------
합계                                                                                     29 kB/s |  25 kB     00:00
연결 확인 실행 중
연결 확인에 성공했습니다.
연결 시험 실행 중
연결 시험에 성공했습니다.
연결 실행 중
  준비 중     :                                                                                                     1/1
  설치 중     : epel-release-8-22.el8.noarch                                                                        1/1
  구현 중     : epel-release-8-22.el8.noarch                                                                        1/1
Many EPEL packages require the CodeReady Builder (CRB) repository.
It is recommended that you run /usr/bin/crb enable to enable the CRB repository.

  확인 중     : epel-release-8-22.el8.noarch                                                                        1/1

설치되었습니다:
  epel-release-8-22.el8.noarch

완료되었습니다!
~~~
~~~
$ sudo dnf config-manager --set-enabled powertools
~~~
~~~
$ sudo dnf install -y htop
Rocky Linux 8 - PowerTools                                                              6.8 MB/s | 5.9 MB     00:00
Extra Packages for Enterprise Linux 8 - x86_64                                           13 MB/s |  14 MB     00:01
마지막 메타자료 만료확인(0:00:01 이전): 2026년 07월 24일 (금) 오후 10시 41분 27초.
종속성이 해결되었습니다.
========================================================================================================================
 꾸러미                    구조                        버전                             저장소                     크기
========================================================================================================================
설치 중:
 htop                      x86_64                      3.2.1-1.el8                      epel                      170 k

연결 요약
========================================================================================================================
설치  1 꾸러미

전체 내려받기 크기: 170 k
설치된 크기 : 396 k
꾸러미 내려받기 중:
htop-3.2.1-1.el8.x86_64.rpm                                                             6.2 MB/s | 170 kB     00:00
------------------------------------------------------------------------------------------------------------------------
합계                                                                                    223 kB/s | 170 kB     00:00
Extra Packages for Enterprise Linux 8 - x86_64                                          1.6 MB/s | 1.6 kB     00:00
GPG키 0x2F86D6A1 가져오는 중:
사용자 ID : "Fedora EPEL (8) <epel@fedoraproject.org>"
지문: 94E2 79EB 8D8F 25B2 1810 ADF1 21EA 45AB 2F86 D6A1
출처 : /etc/pki/rpm-gpg/RPM-GPG-KEY-EPEL-8
키 가져오기에 성공했습니다
연결 확인 실행 중
연결 확인에 성공했습니다.
연결 시험 실행 중
연결 시험에 성공했습니다.
연결 실행 중
  준비 중     :                                                                                                     1/1
  설치 중     : htop-3.2.1-1.el8.x86_64                                                                             1/1
  구현 중     : htop-3.2.1-1.el8.x86_64                                                                             1/1
  확인 중     : htop-3.2.1-1.el8.x86_64                                                                             1/1

설치되었습니다:
  htop-3.2.1-1.el8.x86_64

완료되었습니다!
~~~
