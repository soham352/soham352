#include <iostream>
using namespace std;

int main() {
    // Declare variables
    int num1, num2, sum;

    // Ask for input
    cout << "Enter first number: ";
    cin >> num1;

    cout << "Enter second number: ";
    cin >> num2;

    // Calculate the sum
    sum = num1 + num2;

    // Output the result
    cout << "The sum of " << num1 << " and " << num2 << " is: " << sum << endl;

    // Use an if-else statement
    if (sum > 0) {
        cout << "The sum is positive." << endl;
    } else if (sum < 0) {
        cout << "The sum is negative." << endl;
    } else {
        cout << "The sum is zero." << endl;
    }

    return 0;
}
