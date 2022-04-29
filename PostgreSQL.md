https://gist.github.com/phortuin/2fe698b6c741fd84357cec84219c6667

Dung nhung cau lenh nay oke:

brew uninstall postgresql
brew install postgresql@13
brew services start postgresql@13
brew link postgresql@13 --force

https://www.youtube.com/watch?v=fGOsgMcTP2I

## Command line:
1. psql --version
2. psql postgres : truy cap vap postges
  2.1 \du : lists database roles
  2.2 asf
3. psql -l (psql --list) : hien danh sach db, xong roi thoat
4. CREATE ROLE abc WITH LOGIN PASSWORD 'abc123';
5. 
