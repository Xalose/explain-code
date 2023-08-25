[Back](./index.html)
[introduction](./c++-introduction.html) ]
C++
C++ is an object-oriented program language that updates from another language called C. C++ is often used in program designing, such as Microsoft Internet Explorer, Adobe System etc. As one of the most powerful and popular program languages, C++  has many strengths similar or different from other languages. Firstly, C++ is a highly portable language and is often the language of selection for multi-device, multi-platform app development. Secondly, C++ uses multi-paradigm programming. The Paradigm means the style of programming paradigm concerned about logics, structure, and procedure of the program. C++ is multi-paradigm meaning it follows three paradigms: Generic, Imperative, Object Oriented. 
Therefore, C++ is suitable for students who have had some experience and knowledge on coding. By learning C++, students could get a better understanding of a regulated language so when they learn other languages such as Java or Rust, they will not be confused about many characteristics shown within the code.
Procedures you need for downloading C++:
If you are using Windows, download Dev C++ and start by creating new source code; if you are using MACOS, please download Visual Studio Code(vscode) and other extensions on VScode you need to use(there is an icon called extension) . Or you can download xcode as well. If you want to first try to do C++, you can also go on Replit to create a new C++ program
Start with C++
header file
A header file is a unique characteristic of C++, it’s like a tool or a dlc for your program. Each head file contains a specific function and could help the program achieve a different purpose. For instance, an iostream head file could help C++ users to input and output. The Maths head file could help c++ to calculate different staff. This is similar to Java in that it can import other extensions to make the program more powerful.
name space
name space is specific in C++ programming, it deals with the issue that when two or more programs integrate together, the system may get obscure figuring which version of the function(name) it should use. For example, in two programs, there could be a function called “wanda”, however, these two functions could be different in how they function. The function in program 1 could mean add two numbers together, program 2 could mean add a name into a name list. When integrating, the  program may not know which “wandaP” it should use during compiling, so a namespace gives the program certain space to store the name, and each function then has its own name for the program to choose to use.
function
function is the framework of C++ and is the first step for a program to complete an action. In order to run a program successfully, you need a main function where the compiler starts to compile and complete any action you want it to do. Every function should have a return in the program, if you do not need any return value you should write return 0 to let the program end. In the function, you can let the program print sth on the screen, or you can let it rank the height of students using a list of students’ heights descendingly.  It really depends on what you’ve written in the program. 
variable
variable is a “thing” you create for this program only. For example, if your pet weighs 5 kg, then you can create a variable called  petweight, and this variable will equal to 5 to represent that your pet has 5 kg weight.  Every variable has its own data type, like the dog weighs 5kg so the variable petweight should be an integer instead of a String or Boolean.
The most common variables are:
integer: the numbers 1,2,3,4 etc
String: the normal words are all regarded as string, such as “Class” , “STUDENT”,  combinations with letters and numbers are also included in this data type.
Boolean: Boolean is special in computer language, it determines whether an action is true or wrong, and asks computers to do things depending on the condition. For instance, Kevin may ride a bike if the weather is sunny, or go to school by car if it is raining, we could therefore define a variable called ifraining using boolean data type. If this variable is equal to true, it means today is raining, so Kevin need to go to school by car, if this variable is equal to false, it means today is not raining and Kevin could ride a bike to school.
There are many other variables that are used quite often but not as usually as the staff I previously introduce, for example:
SHORT 
Double
Long 
Long Long
Starting with your first program
Your first program will be a program that could output an addend of two numbers you choose. To achieve this aim, you also need to learn how to input and output in C++
In C++, we express input and output using:
cin>>n;
cout<<n<<”hello world”<<endl;
The line for cin is how C++ input things. However, in C++ there isn’t a term called n, so  the program needs to know what n is and you need to announce it before by telling the program which data type the variable is and what is the exact value of it. For example:
int n=100;
this line informs the program that n is a variable that is int and has a value of 100
Similar in output, you can directly output a string type (i.e.”hello, world”), but for other data types, you also need to announce it. 
int n=100;
cout<<n<<endl;
endl is a special module for output to move into the next line, you can also use ‘\d’ in future to replace it.
Now is the time for you to write the program step by step
Firstly, we construct the basics of the program, in different programs there are different symbols to annotate, in C plus “//” is used to annotate the meaning of the line:
#include <iostream>  // this is to import iostream header file in order to input or output things
using namespace std; // this is to include the namespace for reasons in namespace section
int main(){   // this is the main function of C plus program 
return 0 // each function should have at least one return
}
They are the basic elements of a C++ program. However, C++ could do many unbelievable things, like transfer documents from a laptop to another one, or write/read any document on your laptop. It is not easy to achieve these and it takes very long time to learn. 
Resources you might need for further study:
“C++ primer”
“Thinking in C++”


