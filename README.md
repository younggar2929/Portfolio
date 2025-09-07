#include <iostream>
using namespace std;

int main(){
    int hrs, min;

    cout << "Enter Hour: ";
    if (!(cin >> hrs) || hrs < 0) {
        cout << "Invalid input for hours. Please enter a non-negative integer." << endl;
        return 1;
    }

    cout << "Enter Minutes: ";
    if (!(cin >> min) || min < 0 || min >= 60) {
        cout << "Invalid input for minutes. Please enter an integer between 0 and 59." << endl;
        return 1;
    }

    int total = hrs * 60 + min;

    cout << "Total: " << total << " minutes" << endl;

    return 0;
}
