//# sum-of-even-odd
//Write a program to input an integer N and print the sum of all its even digits and sum of all its odd digits separately.
#include<iostream>
using namespace std;

int main() {
	// Write your code here
	
int num;

    cin >> num;

int evensum=0,oddsum=0,r;

    while( num>0)

    {

        r=num%10;

        if(r%2==0)

        {

            evensum=evensum+r;

        }

        else

        {

            oddsum = oddsum+r;

        }

        num=num/10;

    }

    cout << evensum << " "<< oddsum << endl;
    }
	
