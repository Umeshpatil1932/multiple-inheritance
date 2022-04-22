using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;

namespace umesh6
{
   
class program
 {
    public void info()
{
   String name = "umesh";
   String Class = "SYBCA";
   Console.WriteLine("student name :-" + name);
   Console.WriteLine("Class :-" + Class);
   }
}
  interface exam
{
 void mark();
  }
 class result:program,exam
 {
 public void mark()
 {
    String subject = "c#.net";
     int marks = 28;
 Console.WriteLine("subject:-" + subject);
  Console.WriteLine("marks :-" + marks);
    }
 static void Main(string[] args)
{
   result  rs= new result();
  rs.info();
  rs.mark();
 Console.ReadLine();
}
 }
}

