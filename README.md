# work-hard
-- working Hacker-Rank
##Day 0: Hello World
--#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    // Declare a variable named 'input_string' to hold our input.
    char input_string[105]; 
    
    // Read a full line of input from stdin and save it to our variable, input_string.
    scanf("%[^\n]", input_string); 
    
    // Print a string literal saying "Hello, World." to stdout using printf.
    printf("Hello, World.\n");
    printf("%s",input_string);
    
    // TODO: Write a line of code here that prints the contents of input_string to stdout.
    
    return 0;
}

## Day 1: Data Types
-- #include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int i = 4;
    double d = 4.0;
    char s[] = "HackerRank ";
    int i1;
    double d1;
    char s1[100];
    scanf("%d",&i1);
    scanf("%lf", &d1);
    scanf("%*[\n] %[^\n]",s1);

    printf("%d\n", i+i1);
    printf("%.01lf\n", d+d1);
    printf("%s%s", s, s1);
    return 0;
   ##Practice
   -- #include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() 
{
    char ch;
    char s[10];
    char sen[100];
    scanf("%c",&ch);
    scanf("%s",s);
    scanf("\n");
    scanf("%[^\n]%*c",sen);

    printf("%c\n", ch);
    printf("%s\n", s);
    printf("%s\n", sen);

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
 ##ruby
 --calc prog
 --puts "Enter the 1st number: "
a = gets.chomp .to_f
puts "Enter the operator: "
opr = gets.chomp
puts "Enter the 2nd number: "
b = gets.chomp .to_f


if opr == "+"
   puts (a + b)

elsif opr == "-"
  puts (a - b)

elsif opr == "*"
   puts (a * b)

elsif opr == "/"
    puts (a / b)

else
    puts "Invalid operator"

  end
##array length in ruby
-- soda_type=["sprite" , "mazza" , "lime" , "coco" , "apple" , "kalimark"]
  puts soda_type.length

  puts soda_type.sort
##substring
 -- a=["my name is vkypandi","Arjun reddy","preethi"]
    puts a[0][1,9]
    puts a[1][0..4]
    puts a[2][0..3]


