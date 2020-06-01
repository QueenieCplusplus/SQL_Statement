# SQL_Statement
結構型資料的搜索述句


# Start SQL Server

    mysql -u root -h IP -p port
    
    /r
    
    /q


* Brew install MySQL 

  https://ken.io/note/macos-mysql8-install-config-tutorial
  
  
  
          List of all MySQL commands:
        Note that all text commands must be first on line and end with ';'
        ?         (\?) Synonym for `help'.
        clear     (\c) Clear the current input statement.
        connect   (\r) Reconnect to the server. Optional arguments are db and host.
        delimiter (\d) Set statement delimiter.
        edit      (\e) Edit command with $EDITOR.
        ego       (\G) Send command to mysql server, display result vertically.
        exit      (\q) Exit mysql. Same as quit.
        go        (\g) Send command to mysql server.
        help      (\h) Display this help.
        nopager   (\n) Disable pager, print to stdout.
        notee     (\t) Don't write into outfile.
        pager     (\P) Set PAGER [to_pager]. Print the query results via PAGER.
        print     (\p) Print current command.
        prompt    (\R) Change your mysql prompt.
        quit      (\q) Quit mysql.
        rehash    (\#) Rebuild completion hash.
        source    (\.) Execute an SQL script file. Takes a file name as an argument.
        status    (\s) Get status information from the server.
        system    (\!) Execute a system shell command.
        tee       (\T) Set outfile [to_outfile]. Append everything into given outfile.
        use       (\u) Use another database. Takes database name as argument.
        charset   (\C) Switch to another charset. Might be needed for processing binlog with multi-byte charsets.
        warnings  (\W) Show warnings after every statement.
        nowarning (\w) Don't show warnings after every statement.
        resetconnection(\x) Clean session context.

        For server side help, type 'help contents'


* connect 

For server side help, type 'help contents'

mysql> \r
Connection id:    15
Current database: *** NONE ***


      

* add column to old table = alter...add...
 
 
       alter table schema_name.table_name add column_a int not null;
       
       
* read = select 

       select * from schema_name.table_name;
