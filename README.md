# CmdMgr

# A simple library with 8-bit hash table for procedures.



# Create your table 

HTable table_name;
init(table_name);


# Bind procedures

bind(table_name, proc_name, keyword, error_flag);


# Find procedures

find(table_name, proc_ptr, keyword, error_flag);



# To be compiled with gcc (not g++, cpp extension is used just to acces C++ syntax)

# Uses char* as strings, be careful!

# WIP, new features possible
