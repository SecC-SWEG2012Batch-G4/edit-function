#include <iostream>
#include <cstring>

using namespace std;

struct patientInfo{
     string name,tipFromDoc,recommend;
     int phone;
     char address;
     char bloodType;
     int age,weight,height;
     int id;
     string passcode2,passcode;
};

struct doctor{
     string name;
     int phone;
     char address;
    string passcode;

}d[1000];
void patient();
void edit();
int c = 0;
int id = 1;

int main()
{
    int id;
    int c=0;
    menu();

return 0;
}


void menu(){
char opp;
system("cls");
cout<<"menu"<<endl;
cout<<"1.Administrator"<<endl;
cout<<"2.patient"<<endl;
cout<<"3.doctor"<<endl;
cout<<"4.hospital"<<endl;
cout<<"5.exit"<<endl;


cout<<"enter your choice: ";
enter:
cin>>opp;
if(opp=='1'||opp=='2'||opp=='3'||opp=='4'){
switch(opp){
case '1':
    system("cls");
    Administrator();
    break;
case '2':
    system("cls");
    patient();
    break;
case '3':
    system("cls");
    doctor();
    break;
case '4':
    system("cls");
    hospital();
    break;
case '5':
    system("cls");
    exit(0);
}}
 else
   {
    cout<<"\nwrong input try again: ";
    goto enter;}

}


void patient(){
char c;

cout<<"1.register"<<endl;
cout<<"2.login"<<endl;
cout<<"3.edit"<<endl;
cout<<"4.back "<<endl;
cout<<"enter your choice: ";
enter:
cin>>c;
if(c=='1'||c=='2'||c=='3'||c=='4'){
switch(c){
case '1':
    system("cls");
    newPatient();
    break;
case '2':
    oldPatient();
    break;
 case '3':
     system("cls");
    edit();
    break;
 case '4':
      menu();
    break;
    }}
    else {
    cout<<"\nwrong input try again: ";
    goto enter;
    }
}

void edit()
{
int ch,pid,age1,response;
  string name1;
system ("cls");
cout<<"enter your id : ";
cin>>pid;
for(int i=0; i<c;i++){
        if(pid==p[i].id){
cout<<"\n[1].name : ";
cout<<"\n[2].age : ";
cout<<"\n[3].back : ";
cout<<"\n\nenter your option to edit : \n";
enter:
cin>>ch;
if(ch=='1'||ch=='2'||ch=='3'||ch=='4'){
switch(ch)
{
case '1':

    cout<<"enter the new name : ";
    cin>>name1;
    p[i].name=name1;
    break;

case '2':
    cout<<"\nenter the new age : ";
    cin>>age1;
    p[i].age=age1;
    break;
    }
    }
else  {
        cout<<"\nwrong input try again: ";
    goto enter;
 }

}}

do{
    cout<<"\npress 1 to go back: ";
    cin>>response;
    }while(response!=1);
     system("cls");
     patient();
}
