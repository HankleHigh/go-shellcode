# go-shellcode


修改shellcode

GOOS=windows GOARCH=386 go build -ldflags '-w -s -H=windowsgui'  main.go

upx -9 main.exe

-rwxrwxrwx 1 xi4okv 530K Dec 18 14:21 main.exe

530KB  勉强可以用

-H=windowsgui   是后台运行的参数。
