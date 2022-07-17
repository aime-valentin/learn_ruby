# learn_ruby
beginner-intermediate-advanced rubian

## What Is Ruby?
- scripting language
- developed by Yukihiro Matsumoto in Japan
- true object-oriented language

## Ruby Basic Syntax

puts "Hello, Ruby!"; # print in python 

# RUBY SYNTAX
#a + b (a+b if a and b are local variables)
#a +b (a(+b) if a is a functional call)
#; and \n represents end of statement
#+ - and \ are contiuation of a statment

#HERE DOCUMENT IN RUBY
#allows you to build strings from multiple lines
print <<EOF 
    aime 
    nishimwe 
EOF
#when terminator EOF is quoated, the typeof a quote determines what happens on the following strings 
#for ex, this will have similar impact as the above
print <<"EOF"
    aime 
    nishimwe
EOF
#however the following example is a little different because it takes the strings as executable commmands
print <<`EOF`
    echo "aime nishimwe"
    echo "he computes!" 
EOF

#END and BEGIN COMMAND 
BEGIN{
    # runthis code at the beginning of the program
}
END{
    # run this code at the end of the program
}
#BLOCK COMMENT
=begin
this is i a comment
this is another comment
this is a third comment 
=end

