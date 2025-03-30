# c-DICTIONARY
#include <iostream>
#include <string>
using namespace std;
int main(){
    string a;
    
    cout<<"What do you want to search?: ";
    cin>>a;
    
    if (a== "ABACUS"){
        cout<<"Abacus is a wooden rack that has a metal rods that is believed to be the first computer";
    }else if (a== "NAPIER'S_BONES"){
        cout<<"Uses Ivory Strips or Bones that is marked with numbers to multiply and divide";
    }else if (a== "PASCALINE"){
        cout<<"Works by rotating a wheel. For every revolution, it rotares the neighbouring wheel that totals up on top of the machine";
    }else if(a== "STEPPED_RECKONER"){
        cout<<"it also rotates like the Pascaline but instead it uses flutted drums";
    }else if (a== "ANALYTICAL_ENGINE"){
        cout<<"A machine developed by Charles Babbage capable of performing any mathematical problem";
    }else{
        cout<<"NO WORD IS FOUND";
    }
    
   return 0;
}
