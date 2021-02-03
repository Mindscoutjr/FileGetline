#include <iostream>
  
using namespace std;

int main()

{

    int size=20;
    
    char city[20];
    
    int count=0;
    
    char c;
    
    cout<<"Enter country:\n";
    
    cin.get(c);
    
    while(c!='\n')
    
    {
    
        cout.put(c);
        
        count++;
        
        cin.get(c);
        
    }
    
    cout<<"\nNumber of citys that come up"<<count<<"\n";
    
    cout<<"enter city you wanted: \n";
    
    cin>>city;
    
    cout<<"City name:"<<city<<"\n\n";
    
    
    cout<<"enter city again: \n";
    
    cin.getline(city,size);
    
    cout<<"city name now:"<<city<<"\n\n";
    
    
    cout<<"enter another city again:\n";
    
    cin.getline(city,size);
    
    cout<<"new city name:"<<city<<"\n\n";
    
    return 0;
    
}
