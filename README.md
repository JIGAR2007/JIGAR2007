#include <iostream>
using namespace std;

int main() {
    int n = 4; // number of rows
    int num = 1;
    for (int i = 1; i <= n; i++) {
        // Print spaces
        for (int j = 1; j <= n - i; j++) {
            cout << "  ";
        }
        // Print numbers
        for (int j = 1; j <= i; j++) {
            cout << num << "  ";
            num++;
        }
        cout << endl;
    }
    return 0;
}
