# DockerコンテナからWSL2コンテナへ転生
```
PS C:\Users\sate> podman create python:3.11.1
8f1fd6a76570934b9e35879309c99a5a6a9d373d84aea15fea1ca67ff3670617
PS C:\Users\sate> podman.exe export 8f1fd6a76570934b9e35879309c99a5a6a9d373d84aea15fea1ca67ff3670617 -o python3.11.1.tar
PS C:\Users\sate> wsl --import python3.11 'D:\WSL\python3.11' 'D:\WSL\python3.11.1.tar' --version 2
```
