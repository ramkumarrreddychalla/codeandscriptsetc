1.please look at the create the files like (checked in here)
    alisasexample.sh, j8.sh and j9.sh
2.Modify .bashrc.sh file ()
Rams-MacBook-Pro:~ rammaddela$ cat .bashrc
    
    chmod 777 ~/j8.sh
    chmod 777 ~/j9.sh
    
    #alias j8=$java8/bin:$PATH
    #alias j9=$java9/bin:$PATH
    
    alias j8='source ~/j8.sh'
    alias j9='source ~/j9.sh'
3. source ~/.bashrc
4. use j9 to set to java9 or use j8 to set to java8




