# KASIR-BARBERSHOP

#include <iostream>
using namespace std;

int main ()
{
    int gaya, harga, more, total, pay=0, change;
    string style[6]={"1. FRENCH CROP      = 45K","2. CAESAR CUT       = 30K","3. UNDERCUT         = 25K","4. TAPER CUT        = 45K","5. MOHAWK CUT       = 40K","6. ELSE             = 50K"};
    string extra[4]={"1. HAIRWASH            = 15K","2. POMADE              = 7K","3. HAIRWASH + POMADE   = 20K","4. NORMAL              = -"};
    int i,j;
    

        cout << "___________________________________\n";
        cout << "                                   \n";
        cout << "     WELCOME AT BARBERSHOP BALI    \n";
        cout << "         _________________         \n";
        cout << "             ! STYLE !             \n";
        cout << "___________________________________\n";
        cout << "                                   \n";

                for (i=0;i<6;i++){
                    cout << style[i]<<endl;
                }
        cout << "-----------------------------------\n";
        cout << " CHOOSE YOUR STYLE : ";
        cin  >> gaya;
        cout << "-----------------------------------\n";

         if (gaya<1 || gaya>6){
            cout <<" NOT FOUND! "<< endl; 
        }
    switch (gaya){
        
        case 1 :
        cout << " STYLE FRENCH CROP \n";
        cout << " EXTRA :           \n";
        harga=45000;
        
        for (j=0;j<4;j++){
            cout << extra[j]<<endl;    
        }
        cout << " GET EXTRA? : ";
        cin >> more;

        back:
        switch (more){
            case 1 :
            cout << "\n EXTRA HAIRWASH  \n";
            total=harga+15000;
            cout << "\n PRICE : "<< total << endl;
            cout << " PAY   : ";
            cin >> pay;
            change=pay-total ;
            if (pay<total){
                cout << "YOUR MONEY IS NOT ENOUGH!";
                goto back;
            } 
            else {
                cout << "YOUR CHANGE : "<< change << endl;
            }
            break ;

            case 2 :
            cout << "\n EXTRA POMADE  \n";
            total=harga+7000;
            cout << " PRICE : "<< total << endl;
            cout << " PAY   : ";
            cin >> pay;
            change=pay-total ;
            if (pay<total){
                cout << "YOUR MONEY IS NOT ENOUGH!";
                goto back;
            } 
            else {
                cout << "YOUR CHANGE : "<< change << endl;
            }
            break ;

            case 3 :
            cout << "\n EXTRA HAIRWASH + POMADE  \n";
            total=harga+20000;
            cout << " PRICE : "<< total << endl;
            cout << " PAY   : ";
            cin >> pay;
            change=pay-total ;
            if (pay<total){
                cout << "YOUR MONEY IS NOT ENOUGH!";
                goto back;
            } 
            else {
                cout << "YOUR CHANGE : "<< change << endl;
            }
            break ;

            case 4 :
            cout << "\n NORMAL  \n";
            total=harga;
            cout << " PRICE : "<< total << endl;
            cout << " PAY   : ";
            cin >> pay;
            change=pay-total ;
            if (pay<total){
                cout << "YOUR MONEY IS NOT ENOUGH!";
                goto back;
            } 
            else {
                cout << "YOUR CHANGE : "<< change << endl;
            }
            break ;
        }
        break ;
        case 2 :
        cout << " STYLE CAESAR CUT \n";
        cout << " EXTRA :           \n";
        harga=30000;
        
        for (j=0;j<4;j++){
            cout << extra[j]<<endl;    
        }
        cout << " GET EXTRA? : ";
        cin >> more;

        back1:
        switch (more){
            case 1 :
            cout << "\n EXTRA HAIRWASH  \n";
            total=harga+15000;
            cout << " PRICE : "<< total << endl;
            cout << " PAY   : ";
            cin >> pay;
            change=pay-total ;
            if (pay<total){
                cout << "YOUR MONEY IS NOT ENOUGH!";
                goto back1;
            } 
            else {
                cout << "YOUR CHANGE : "<< change << endl;
            }
            break ;

            case 2 :
            cout << "\n EXTRA POMADE  \n";
            total=harga+7000;
            cout << " PRICE : "<< total << endl;
            cout << " PAY   : ";
            cin >> pay;
            change=pay-total ;
            if (pay<total){
                cout << "YOUR MONEY IS NOT ENOUGH!";
                goto back1;
            } 
            else {
                cout << "YOUR CHANGE : "<< change << endl;
            }
            break ;

            case 3 :
            cout << "\n EXTRA HAIRWASH + POMADE  \n";
            total=harga+20000;
            cout << " PRICE : "<< total << endl;
            cout << " PAY   : ";
            cin >> pay;
            change=pay-total ;
            if (pay<total){
                cout << "YOUR MONEY IS NOT ENOUGH!";
                goto back1;
            } 
            else {
                cout << "YOUR CHANGE : "<< change << endl;
            }
            break ;

            case 4 :
            cout << "\n NORMAL  \n";
            total=harga;
            cout << " PRICE : "<< total << endl;
            cout << " PAY   : ";
            cin >> pay;
            change=pay-total ;
            if (pay<total){
                cout << "YOUR MONEY IS NOT ENOUGH!";
                goto back1;
            } 
            else {
                cout << "YOUR CHANGE : "<< change << endl;
            }
            break ;
        }
        break ;
        case 3 :
        cout << " STYLE UNDERCUT \n";
        cout << " EXTRA :           \n";
        harga=25000;
        
        for (j=0;j<4;j++){
            cout << extra[j]<<endl;    
        }
        cout << " GET EXTRA? : ";
        cin >> more;

        back2:
        switch (more){
            case 1 :
            cout << "\n EXTRA HAIRWASH  \n";
            total=harga+15000;
            cout << " PRICE : "<< total << endl;
            cout << " PAY   : ";
            cin >> pay;
            change=pay-total ;
            if (pay<total){
                cout << "YOUR MONEY IS NOT ENOUGH!";
                goto back2;
            } 
            else {
                cout << "YOUR CHANGE : "<< change << endl;
            }
            break ;

            case 2 :
            cout << "\n EXTRA POMADE  \n";
            total=harga+7000;
            cout << " PRICE : "<< total << endl;
            cout << " PAY   : ";
            cin >> pay;
            change=pay-total ;
            if (pay<total){
                cout << "YOUR MONEY IS NOT ENOUGH!";
                goto back2;
            } 
            else {
                cout << "YOUR CHANGE : "<< change << endl;
            }
            break ;

            case 3 :
            cout << "\n EXTRA HAIRWASH + POMADE  \n";
            total=harga+20000;
            cout << " PRICE : "<< total << endl;
            cout << " PAY   : ";
            cin >> pay;
            change=pay-total ;
            if (pay<total){
                cout << "YOUR MONEY IS NOT ENOUGH!";
                goto back2;
            } 
            else {
                cout << "YOUR CHANGE : "<< change << endl;
            }
            break ;

            case 4 :
            cout << "\n NORMAL  \n";
            total=harga;
            cout << " PRICE : "<< total << endl;
            cout << " PAY   : ";
            cin >> pay;
            change=pay-total ;
            if (pay<total){
                cout << "YOUR MONEY IS NOT ENOUGH!";
                goto back2;
            } 
            else {
                cout << "YOUR CHANGE : "<< change << endl;
            }
            break ;
        }
        break ;
        case 4 :
        cout << " STYLE TAPER CUT \n";
        cout << " EXTRA :           \n";
        harga=45000;
        
        for (j=0;j<4;j++){
            cout << extra[j]<<endl;    
        }
        cout << " GET EXTRA? : ";
        cin >> more;

        back3:
        switch (more){
            case 1 :
            cout << "\n EXTRA HAIRWASH  \n";
            total=harga+15000;
            cout << " PRICE : "<< total << endl;
            cout << " PAY   : ";
            cin >> pay;
            change=pay-total ;
            if (pay<total){
                cout << "YOUR MONEY IS NOT ENOUGH!";
                goto back3;
            } 
            else {
                cout << "YOUR CHANGE : "<< change << endl;
            }
            break ;

            case 2 :
            cout << "\n EXTRA POMADE  \n";
            total=harga+7000;
            cout << " PRICE : "<< total << endl;
            cout << " PAY   : ";
            cin >> pay;
            change=pay-total ;
            if (pay<total){
                cout << "YOUR MONEY IS NOT ENOUGH!";
                goto back3;
            } 
            else {
                cout << "YOUR CHANGE : "<< change << endl;
            }
            break ;

            case 3 :
            cout << "\n EXTRA HAIRWASH + POMADE  \n";
            total=harga+20000;
            cout << " PRICE : "<< total << endl;
            cout << " PAY   : ";
            cin >> pay;
            change=pay-total ;
            if (pay<total){
                cout << "YOUR MONEY IS NOT ENOUGH!";
                goto back3;
            } 
            else {
                cout << "YOUR CHANGE : "<< change << endl;
            }
            break ;

            case 4 :
            cout << "\n NORMAL  \n";
            total=harga;
            cout << " PRICE : "<< total << endl;
            cout << " PAY   : ";
            cin >> pay;
            change=pay-total ;
            if (pay<total){
                cout << "YOUR MONEY IS NOT ENOUGH!";
                goto back3;
            } 
            else {
                cout << "YOUR CHANGE : "<< change << endl;
            }
            break ;
        }
        break ;
        case 5 :
        cout << " STYLE MOWAHK \n";
        cout << " EXTRA :           \n";
        harga=40000;
        
        for (j=0;j<4;j++){
            cout << extra[j]<<endl;    
        }
        cout << " GET EXTRA? : ";
        cin >> more;

        back4:
        switch (more){
            case 1 :
            cout << "\n EXTRA HAIRWASH  \n";
            total=harga+15000;
            cout << " PRICE : "<< total << endl;
            cout << " PAY   : ";
            cin >> pay;
            change=pay-total ;
            if (pay<total){
                cout << "YOUR MONEY IS NOT ENOUGH!";
                goto back4;
            } 
            else {
                cout << "YOUR CHANGE : "<< change << endl;
            }
            break ;

            case 2 :
            cout << "\n EXTRA POMADE  \n";
            total=harga+7000;
            cout << " PRICE : "<< total << endl;
            cout << " PAY   : ";
            cin >> pay;
            change=pay-total ;
            if (pay<total){
                cout << "YOUR MONEY IS NOT ENOUGH!";
                goto back4;
            } 
            else {
                cout << "YOUR CHANGE : "<< change << endl;
            }
            break ;

            case 3 :
            cout << "\n EXTRA HAIRWASH + POMADE  \n";
            total=harga+20000;
            cout << " PRICE : "<< total << endl;
            cout << " PAY   : ";
            cin >> pay;
            change=pay-total ;
            if (pay<total){
                cout << "YOUR MONEY IS NOT ENOUGH!";
                goto back4;
            } 
            else {
                cout << "YOUR CHANGE : "<< change << endl;
            }
            break ;

            case 4 :
            cout << "\n NORMAL  \n";
            total=harga;
            cout << " PRICE : "<< total << endl;
            cout << " PAY   : ";
            cin >> pay;
            change=pay-total ;
            if (pay<total){
                cout << "YOUR MONEY IS NOT ENOUGH!";
                goto back4;
            } 
            else {
                cout << "YOUR CHANGE : "<< change << endl;
            }
            break ;
        }
        break ;
        case 6 :
        cout << " MY STYLE \n";
        cout << " EXTRA :           \n";
        harga=50000;
        
        for (j=0;j<4;j++){
            cout << extra[j]<<endl;    
        }
        cout << " GET EXTRA? : ";
        cin >> more;

        back5:
        switch (more){
            case 1 :
            cout << "\n EXTRA HAIRWASH  \n";
            total=harga+15000;
            cout << " PRICE : "<< total << endl;
            cout << " PAY   : ";
            cin >> pay;
            change=pay-total ;
            if (pay<total){
                cout << "YOUR MONEY IS NOT ENOUGH!";
                goto back5;
            } 
            else {
                cout << "YOUR CHANGE : "<< change << endl;
            }
            break ;

            case 2 :
            cout << "\n EXTRA POMADE  \n";
            total=harga+7000;
            cout << " PRICE : "<< total << endl;
            cout << " PAY   : ";
            cin >> pay;
            change=pay-total ;
            if (pay<total){
                cout << "YOUR MONEY IS NOT ENOUGH!";
                goto back5;
            
            } 
            else {
                cout << "YOUR CHANGE : "<< change << endl;
            }
            break ;

            case 3 :
            cout << "\n EXTRA HAIRWASH + POMADE  \n";
            total=harga+20000;
            cout << " PRICE : "<< total << endl;
            cout << " PAY   : ";
            cin >> pay;
            change=pay-total ;
            if (pay<total){
                cout << "YOUR MONEY IS NOT ENOUGH!";
                goto back5;
            } 
            else {
                cout << "YOUR CHANGE : "<< change << endl;
            }
            break ;

            case 4 :
            cout << "\n NORMAL  \n";
            total=harga;
            cout << " PRICE : "<< total << endl;
            cout << " PAY   : ";
            cin >> pay;
            change=pay-total ;
            if (pay<total){
                cout << "YOUR MONEY IS NOT ENOUGH!";
                goto back5;
            } 
            else {
                cout << "YOUR CHANGE : "<< change << endl;
            }
            break ;
        }
        break ;
    }
    cout << endl;
    cout << "-----------------------\n";
    cout << " |     THANK YOU!    | \n";
    cout << " | SEE YOU NEXT TIME | \n";
    cout << "-----------------------\n";
}
