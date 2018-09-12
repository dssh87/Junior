# -github 활용
  
1. 필요없는 Repo의 directory 삭제  
  
$ git rm -r --cached .idea(해당 폴더 또는 파일 이름)  
  
rm 'angularjs/component/.idea/.name'  
rm 'angularjs/component/.idea/component.iml'  
..... 등 내용 여러줄 출력 / 읽어오는 명령어  
  
$ git commit -m "remove webstorm .idea(해당 폴더 또는 파일 이름) directory"  
  
[master 80de3cc] remove webstorm .idea directory  
 10 files changed, 352 deletions(-)  
 delete mode 100644 angularjs/component/.idea/.name  
 delete mode 100644 angularjs/component/.idea/component.iml  
..... 등 내용 여러줄 출력 / 삭제하는 명령어  
  
$ git push origin master  
  
Counting objects: 7, done.  
Delta compression using up to 4 threads.  
... 등 내용 출력 / 푸쉬하는 명령어  
  
→ github의 해당 Repo를 확인해보면 지우려고 했던 폴더 또는 파일이 삭제된 것을 알 수 있다.  
