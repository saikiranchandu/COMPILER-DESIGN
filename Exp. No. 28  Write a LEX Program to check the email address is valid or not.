%{
int flag=0;
%}
%%
[a-z . 0-9]+@[a-z]+".com"|".in" { flag=1; }
%%
int main()
{
yylex();
if(flag==1)
printf("Accepted");
else
printf("Not Accepted");
}
int yywrap()
{ return 1;
}
