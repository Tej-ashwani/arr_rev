# arr_rev
//reverse of array
#include<iostream>
using namespace std;
void reverse(int arr[], int start,int end){
    while(start<end){
        int temp=arr[start];
        arr[start]=arr[end];
        arr[end]=temp;
        start++;
        end--;
    }
    return;
    

}
int main(){
    int size;
    cin>>size;
    int arr[size];

    
    
    
    for(int i=0;i<size;i++){
        cin>>arr[i];
        }
        reverse(arr,0,size-1);

        cout<<"the reverse of array is";
        for(int i=0;i<size;i++){
            cout<<arr[i];
        }
        return 0;}

            
