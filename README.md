# go-learn-modul

# 
untuk upgrade modul major version / perubahan yang besar sehingga penguna modul harus ikut melakukan update sintak / code
sebaik nya update file go.mod pada bagian 
module github.com/ugik-dev/go-learn-modul
tambahkan v2 sehingga menjadi 
module github.com/ugik-dev/go-learn-modul/v2
dan lakukan release tag lagi ke seperti tag v2.0.0
# update-step :
1. git add ( use . for all or use path or filename)
2. git commit -m "message"
3. git push origin master
4. git tag v1.5.3
5. git push origin v1.5.3

# instalation 
for first time instalation use : go get github.com/ugik-dev/go-learn-modul/
for update depedency : modif file go.mod version and exce go get 

