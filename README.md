# lesson1-hw
task1
Console.Clear();
Console.Write("Enter a ");
int a = int.Parse(Console.ReadLine());
Console.Write("Enter b ");
int b = int.Parse(Console.ReadLine());
int max = a;
int min = a;
if  ( a > max ) max = a;
else
if ( b > max ) max = b;
else
if ( a < min ) min = a;
else
if ( b < min ) min = b;
{
    Console.Write("max = ");
    Console.WriteLine(max);
    Console.Write("min = ");
    Console.WriteLine(min);
}






task2
Console.Clear();
Console.Write("Enter b ");
int b = int.Parse(Console.ReadLine());
Console.Write("Enter a ");
int a = int.Parse(Console.ReadLine());
Console.Write("Enter c ");
int c = int.Parse(Console.ReadLine());
int max = a;
if (a>max) max=a;
if (b>max) max=b;
if (c>max) max=c;
Console.Write("max = ");
Console.WriteLine(max);





task3
Console.Clear();
Console.Write("Enter a ");
int a = int.Parse(Console.ReadLine());
int remDiv = a % 2;
if(remDiv == 0)
{
    Console.WriteLine("Да");
}
else
{
    Console.WriteLine("Нет");
}






task 4

Console.Clear();
Console.Write("Enter a ");
int a = int.Parse(Console.ReadLine());

int i = 1;
while (i <= a)
{
    Console.WriteLine($"{i}");
     i=i+2;
}
for (i=1; i <= a; i++)
{
    if(i%2==0)
    {Console.Write ($"{i+","}");

}
}
