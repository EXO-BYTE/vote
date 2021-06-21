# vote
to find eligibility to vote
#include<iostream>
using namespace std;

int main() {

    int age;
    cout << "Enter age of a user:";
    cin>>age;

    if (age >= 18) {
        cout << "You are eligible for voting";
    } else {
        cout << "You are not eligible for voting";
       cout<<"please wait till you turn 18:)";
    }

    return 0;
