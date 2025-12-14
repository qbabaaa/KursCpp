#include <iostream>
using namespace std;

int main() {
    int liczba;

    do {
        cout << "podaj liczbe od 1 do 100 ";
        cin >> liczba;

        if (liczba < 1 || liczba > 100) {
            cout << "zła liczba\n";
        }

    } while (liczba < 1 || liczba > 100);

    cout << "ok";

    return 0;
}


