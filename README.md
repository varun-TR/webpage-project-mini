# webpage-project-mini
#include<iostream>
#include<unistd.h>
#include<string>
#include<stdlib.h>
using namespace std;
void url();

int main()
{ 
	int ch;
	label:
	cout<<"\n\t\t Welcome To Webpage List \n\t\t"<<endl;
	cout<<"\n\t\t1.Google\n\t\t2.Youtube\n\t\t3.Facebook\n\t\t4.Instgram\n\t\t5.To desire site"<<endl;
	cout<<"\n\t\t Enter your choice : ";
   	cin>>ch;
	
	switch(ch)
	{
		case 1 : system("start www.google.com");
		          system("cls");
		        goto label;
		         break;
		         case 2 : system ("start www.youtube.com");
		           system("cls");
		            goto label;
		            break;
		            case 3 : system("start www.facebook.com");
		              system("cls");
		               goto label;
		              break;
		              case 4 : system("start www.instagram.com");
		                system("cls");
		                 goto label;
		              break;
		              
		             case 5 :  url();
		             
		                        break;
		             
					           
		              default : cout<<"\n\t\t\t\tinvalid choice";
		              sleep(1);
		                system("cls");
		                       goto label;
		                       break;
	}
	return 0;

};

void url()
{
	system("cls");
	cout << "Enter the Url: " << endl;
  string username;
  cin >> username;

 system(std::string("start " + username).c_str());
 
}
