#include <iostream>
#include <string>
#include <iomanip>

using namespace std;

struct Product {
    string name;
    double price;
    int quantity;
};

int main() {
    Product p;
    cout << "Enter name: ";
    getline(cin, p.name);
    cout << "Enter price: ";
    cin >> p.price;
    cout << "Enter quantity: ";
    cin >> p.quantity;

    cout << fixed << setprecision(2);
    cout << "Total: " << p.price * p.quantity << " UAH" << endl;
    return 0;
}
