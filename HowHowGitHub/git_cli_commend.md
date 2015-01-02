#### 깃헙 터미널 명령어
| [시작하기](./README.md) |

<클론 받을때(웹주소이용)>  
    git clone https://github.com/kimsg1984/android_training_translation.git

<처음 사용시>

    git init
    git add *
    git commit -m "설명"
    git remote add origin  
    git push -u origin master 

<업데이트시>

    git add *
    git commit -m "설명"
    git push -u origin master


<쉘 스크립트>

    #!/bin/bash
    git add *
    git push 
    git commit -m "$1"
    git push origin master
    exit

<트리 문제시>

    git reset --hard


<참고>  
- http://kimseunghyun76.tistory.com/116
