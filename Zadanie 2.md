{$APPTYPE CONSOLE}
uses 
SysUtils;
Windows;

var;
i,n :integer;
res :string;

function f(i2:integer;var s:string)boolean;
var j>l:integerbegin
for j:= 1 to i2 do
for l:= 1 to i2 do
begin 
fi j*j+1*1=i2 then
begin
result:=true;
s:inttostr(i2)+'='+inttostr(j)+'^2'+inttostr(l)+'^2';
end;
end;
end;

begin

writeln('Vvedite N');
Readln(n);

for i:1 to n do 
begin
if f(i,res)then writeln(res);
end;



Readln;
end.
 
