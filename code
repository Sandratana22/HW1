//Homework-1

#include <iostream> 

using namespace std; 

//Printing an integer to a binary
int main() {
    int number; 
    cout << "Enter an integer number: " << endl; 
    cin >> number; 

    int binaryofInt[32]; //Initialized the binary of Int to 32 bits
    int length = 0; //length of the number; 

//Using while loop to find the length of the binary 
    while(number > 0) {
        binaryofInt[length] = number % 2; 
        number /= 2; 
        length++; 
    }

    cout << "The Binary number is: " << endl; 
    for(int i = length -1; i >= 0; i--){ //We use for loop here to find the length of the number
        cout << binaryofInt[i]; 
    }
    cout << endl; 

    return 0; 
}
