#include <iostream>
    #include <string>
    
    using namespace std;
    
    int main() {
        string name;
        cout << "input name: ";
        cin >> name;
    
        string id;
        cout << "input id: ";
        cin >> id;
        cout << endl;
    
        // For 迴圈
        int n_for;
        cout << "Please input a number n for FOR loop: ";
        cin >> n_for;
    
        int total_for = 0;
        for (int i = 1; i <= n_for; i++) {
            total_for += i;
        }
        cout << "for loop : The sum of 1 to " << n_for << " is " << total_for << endl << endl;
    
    
        // While 迴圈
        int n_while;
        cout << "Please input a number n for WHILE loop: ";
        cin >> n_while;
    
        int total_while = 0;
        int j = 1;
        while (j <= n_while) {
            total_while += j;
            j++;
        }
        cout << "while loop : The sum of 1 to " << n_while << " is " << total_while << endl << endl;
    
    
        // Do-While 迴圈
        int n_do_while;
        cout << "Please input a number n for DO-WHILE loop: ";
        cin >> n_do_while;
    
        int total_do_while = 0;
        int k = 1;
        do {
            total_do_while += k;
            k++;
        } while (k <= n_do_while);
        cout << "do-while loop : The sum of 1 to " << n_do_while << " is " << total_do_while << endl;
    
        return 0;
    }
