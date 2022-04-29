https://gist.github.com/phortuin/2fe698b6c741fd84357cec84219c6667

Dung nhung cau lenh nay oke:

brew uninstall postgresql
brew install postgresql@13
brew services start postgresql@13
brew link postgresql@13 --force

https://www.youtube.com/watch?v=fGOsgMcTP2I

## Command line: 
1. psql --version
##### 2.  psql postgres : truy cap vap postges (muon dung postgres thi phai vao postgres truoc)
3. => \du : lists database roles
4. => \l : danh sach user
5. psql -l (psql --list) : hien danh sach db, xong roi thoat
6. CREATE ROLE abc WITH LOGIN PASSWORD 'abc123';
7. ALTER ROLE abc CREATEDB;
8. 
