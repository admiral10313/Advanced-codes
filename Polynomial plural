#include <stdio.h>
#include <iostream>

using namespace std;

//sakhtar braye zarib haye Chandjomlei
typedef struct Zarib {

    int Z[100];

};

//sakhtar brayw tvan haye har bakhsh az Chandjomlei
typedef struct TAvan {

    int T[100];

};

//tabe braye frayand tavan
int Tavan(int x, int p) {

    if (p == 0) {
        return 1;
    }

    if (p == 0 && x == 0) {
        return 0;
    }

    if (p == 1) {
        return x;
    }

    int H = x;


    for (int i = 0; i < p; i++) {

        H *= x;

    }
    return H;
}

//tabe frayand koli
int frayand() {
    Zarib p1;
    TAvan s1;

    cout << "\n\t\ttedad jomalat ra vared konid : (mix 100)" << endl;

    int tedad_j;
    cin >> tedad_j;

    long long int hasel;

    for (int i = 0; i < tedad_j; i++) {

        cout << "\n\t\tZarib jomle[" << i + 1 << "] ra vared konid : " << endl;
        cin >> p1.Z[i];

        cout << "\n\t\ttavan {X} jomle[" << i + 1 << "] ra vared konid : " << endl;
        cin >> s1.T[i];

        cout << "\n\t\tadad {X} jomle[" << i + 1 << "] ra vared konid : " << endl;
        int x;
        cin >> x;

        cout << "\n\t\t---------------------------------" << endl;

        hasel = (p1.Z[i]) * Tavan(x, (s1.T[i]));

    }

    return hasel;
}

//main asli
int main() {

    cout << "\n\t\thasel : " << frayand() << endl;

    return 0;
}
