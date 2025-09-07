#include <iostream>
using namespace std;

int main(){
    int hrs, min;

    cout << "Enter Hour:";
    cin >> hrs;

    cout << "Enter Minutes:";
    cin >> min;

    int total = hrs * 60 + min;

    cout << "Total: " << total << " minutes" << endl;

}
