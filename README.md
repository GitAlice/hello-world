# hello-world
Welcome to git

//Try edit code
#include<iostream.h>
struct Student
{
   char name[10];
   char score[4];
   int average;
};

void main()
{  
   int i,sum=0;
   Student st;
   cout<<"The student's name:"<<endl;
   cin>>st.name;
   cout<<"Please enter the student's score:"<<endl;
   for(i=0;i<4;i++)
   cin>>st.score[i];
   for(i=0;i<4;i++)
   sum+=st.score[i];
   st.average=sum/4;
   cout<<"The student average:"<<st.average<<endl;
}
