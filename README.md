# Decision-Statement
The decision control statements are the decision making statements that decides the order of execution of statements based on the conditions. In the decision making statements the programmer specify which conditions are to be executed or tested with the statements to be executed if the condition is true or false.


//1.Prog to declare the price of book with "if" staement
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

#include<iostream>
int main()
{
 int price;
 cout<<"\n Enter the price of book";
 cin>>price;
 if(price<=600)
 {
  cout<<"\n Hurry up buy the book";
 }
 return 0;
}
========================================================

//2.Prog to check the equivalence
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

#include<iostream>
int main()
{
  int m,n;
  cout<<"Enter the numbers";
  cin>>m>>n;
  if(m-n==0)
  {
   cout<<"\n Two numbers are equivalent";
  }
 return 0;
}

=============================================
  
  //3.use library function strlen()
  ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  
  #include<iostream>
  int main()
  {
    static char nm[]="Hello";
    if(strlen(nm))
    {
     cout<<"The string is not empty";
     }
    return 0;
 }
 
 ====================================
 
 //4.Prog to find percent
 ~~~~~~~~~~~~~~~~~~~~~~~
 
 #include<iostream>
 int main()
 {
   float per;
   cout<<"\n Enter the percentage:";
   cin>>per;
   if(per>=90 && per<=100)
   cout<<"\n Distinction";
   if(per>=70 && per<=90)
   cout<<"\n First class";
   if(per>=50 && per<=70)
   cout<<"\n second class";
   if(per>=40 && per<=50)
   cout<<"\n pass";
   if(per<40)
   cout<<"\n Fail";
   return 0;
  }
  
  ==========================
  
  //6.Prog to enter age and display message
  ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  
  #include<iostream>
  #include<string.h>
  int main()
  {
   int age;
   cout<<"Enter the age;
   cin>>age;
       if(age>=18)
        {
         cout<<"you are eligible for voting";
        }
        
        else
        {
         cout<<"You are not eligible for voting "<<endl;
         cout<<"Wait for"<<18-age<<"year";
        }
        
        return 0;
   }
   
   =================================================
   
   //7.Implementation of if-else
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
   
   #include<iosream>
   int main()
   {
     int score;
     cout<<"Enter the run scored of batman:";
     cin>>score;
     
     if(score>=50)
     cout<<"\n Congrats";
     
     else
     if(score<50)
     cout<<"\n Come on!!";
     return 0;
   }
   
   ===============================
   
   //8.To print the largest of the three numbers
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
   
   #include<iostream>
   int main()
   {
     int a,b,c;
     cout<<"\n Enter three number:";
     cin>>a>>b>>c;
     if(a>b)
        {
          if(a>c)
             cout<<"\n a is largest";
          else
             cout<<"\n b is largest";
        }
        
     else
        {
         if(b>c)
         cout<<"\n b is largest";
         else
         cout<<"\n c is largest";
       }
       return 0;
    }
    
    =================================
    
    //9.claculate energy bill
    ~~~~~~~~~~~~~~~~~~~~~~~~~~
    
    
       
     
   
