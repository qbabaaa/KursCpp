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


#include <iostream>
using namespace std;

int main() {
    int liczba;
    bool pierwsza = true;

    cout << "Podaj liczbe która jest większa od 1 ";
    cin >> liczba;

    for (int i = 2; i < liczba; i++) {
        if (liczba % i == 0) {
            pierwsza = false;
            break;
        }
    }

    if (pierwsza && liczba > 1) {
        cout << "Liczba " << liczba << " jest pierwsza." << endl;
    }
    else {
        cout << "Liczba " << liczba << " nie jest  pierwsza." << endl;
    }

    return 0;
}


