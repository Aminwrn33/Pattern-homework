#include <iostream>

using namespace std;

int main()
{
    const int size = 5;

    cout << "Pattern 208\n\n";

    for (int i = 0; i < size; ++i) {\

        for (int j = 0; j < size; ++j) {

            if (i == j) {
                cout << i + 1 << " ";
            }
            else {
                cout << "0 ";
            }
        }
        cout << endl;
    }







}

