#include <iostream>
using namespace std;

void pilihanBoolean (){
    cout << " Welcome to the Boolean Based Calculator program " ;
    cout << "\n    Project by Group 6 Basic's Programming \n" ;
    cout << "\n Number 0 is FALSE and 1 is TRUE \n" ;
    cout << "\n Please choose the logic operation \n" ;
    cout << "1. AND\n" ;
    cout << "2. OR\n" ;
    cout << "3. NOT\n" ;
    cout << "4. XOR\n" ;
    cout << "5. NAND\n" ;
    cout << "6. NOR\n" ;
    cout << "7. XNOR\n" ;
    cout << "8. Keluar\n" ;
    cout << "Masukkan pilihan anda <3 (1-6): ";
}

int main () {
    int pilihan;
    bool x, y, hasil;
    
    do {
        pilihanBoolean();
        cin >> pilihan;
        
        switch (pilihan) {
            case 1:
            
            cout << "Please input the value of X (0 atau 1) ";
            cin >> x;
            cout << "Please input the value of y (0 atau 1) ";
            cin >> y;
            hasil = x && y;
            cout << "The result X AND Y is " << hasil ;
            cout << "\n0 is FALSE and 1 is TRUE " << endl;
            exit(0);
            
            case 2:
            
            cout << "Please input the value of X (0 atau 1) ";
            cin >> x;
            cout << "Please input the value of y (0 atau 1) ";
            cin >> y;
            hasil = x || y;
            cout << "The result X OR Y is " << hasil ;
            cout << "\n0 is FALSE and 1 is TRUE " << endl ;
            exit(0);
            
            case 3:
            
            cout << "Please input the value of X (0 atau 1) ";
            cin >> x;
            hasil = !x;
            cout << "The result NOT X is " << hasil ;
            cout << "\n0 is FALSE and 1 is TRUE " << endl;
            exit (0);
            
            case 4:
            
            cout << "Please input the value of X (0 atau 1) ";
            cin >> x;
            cout << "Please input the value of y (0 atau 1) ";
            cin >> y;
            hasil = x ^ y;
            cout << "The result X XOR Y is " << hasil ;
            cout << "\n0 is FALSE and 1 is TRUE " << endl;
            exit(0);
            
            case 5:
            
            cout << "Please input the value of X (0 atau 1) ";
            cin >> x;
            cout << "Please input the value of y (0 atau 1) ";
            cin >> y;
            hasil = !(x && y);
            cout << "The result X NAND Y is " << hasil ;
            cout << "\n0 is FALSE and 1 is TRUE " << endl;
            exit(0);
            
            case 6:
            cout << "Please input the value of X (0 atau 1) ";
            cin >> x;
            cout << "Please input the value of y (0 atau 1) ";
            cin >> y;
            hasil = !(x || y);
            cout << "The result X NOR Y is " << hasil ;
            cout << "\n0 is FALSE and 1 is TRUE " << endl ;
            exit(0);
            
            case 7:
            
            cout << "Please input the value of X (0 atau 1) ";
            cin >> x;
            cout << "Please input the value of y (0 atau 1) ";
            cin >> y;
            hasil = !(x ^ y);
            cout << "The result X XNOR Y is " << hasil ;
            cout << "\n0 is FALSE and 1 is TRUE " << endl;
            exit(0);
            
            case 8:
            
            cout << "Exit the programs. Thank you and LONG LIVE" ;
            exit(0);
            
            default:
            cout << "The choice is not valid. Please try again :(";
            exit(0);
        }
    } while (pilihan != 7);
    
    return 0;
}
