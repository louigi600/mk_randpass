# mk_randpass
Just another bash parametric random password generator 

usage: mk_randpass [OPTIONS]

OPTIONS

-S <value>      :A single quoted, optionally "C-style string" if you need to escape characters, containing the special character list you want to pic from (default is $'!@#$%^&*()_-+=~?/<>;:{}[]"\'' )
  
-v              :Enable debugging output
  
-u <value>      :The number of upper case characters to be included in the password (default 1)
  
-s <value>      :The number of special characters to be included in the password (default 1)
  
-n <value>      :The number of numerical digits to be included in the password (default 1)
  
-l <value>      :The overall password lenght (default 8)
  
-h              :Show this help message
