#include<iostream> \r\n
using namespace std;\r\n
int main(){\r\n

int arr[4][5]//2D array to store the numbers\r\n
intx,y;\r\n

//initialize the array with numbers from 1 to 20
for(x=0;x<4;x++){
for(y=0;y<5;y++){
 
arr[x][y] =x*5+y+1;
}
}
//print array in grouped format
for(x=0; x<4;x++){
for(x=0;y<5;x++){
cout<<arr[x][y]<<"\t";
}
cout<<endl;
}
return 0;

