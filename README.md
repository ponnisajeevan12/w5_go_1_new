git clone <_________> w5_go_1_new
go mod init github.com/ponnisajeevan12/w5_go_1_new
go run .\main.go .\Greeting.go .\advanceGreeting.go
go build -o myfirstgo.exe
.\myfirstgo.exe
echo "# w5_go_1_new" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote remove origin
git remote add origin https://github.com/ponnisajeevan12/w5_go_1_new.git
git push -u origin master
git add .
git commit -m "Declaring func - 3 files"
git push