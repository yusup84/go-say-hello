# readme
1. membuat folder untuk module dan app
2. untuk module folder nya go-say-hello dan untuk app nama foldernya app-say-hello
3. buat repository di github namanya go-say-hello
4. buka folder module di vs code dan ketik go mod init github.com/yusup84/go-say-hello
5. git init kemudian git add .
6. git commit -m "membuat module say-hello"
8. git remote add origin https://github.com/yusup84/go-say-hello.git
9. git push -u origin master
10. cek di github nasuk ga semua yg di commit
11. rilis version/tag module nya di github:
    1.git tag v1.0.0
    2.git push origin v1.0.0
12. untuk upgrade module kita hanya cukup membuat tag baru di git
13. git add . 
14. git commit -m "update SayHello"
15. git push origin master
16. updgrade tag/version:
    - git tag v1.5.0
    - git push origin v1.5.0
17. major upgrade, sebaikny klo major ganti nama module biar tidak mengganggu module yg lama
18. contoh: module github.com/yusup84/go-say-hello/v2 ditambahin v2 paling belakang
19. 