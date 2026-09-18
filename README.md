#include<iostream>
using namespace std;
int main(){
    int a;
    float diemchuyencan;

    while(true){

    cout << " Hay nhap diem qua trinh cua ban: " << endl;
    cin >> a;

    if (a>=0 && a<=10){
    diemchuyencan = a*0.5;

    cout << "Diem chuyen can cua ban la: " << diemchuyencan << endl;
    
    break;
}
    else{
        cout << "Diem qua trinh khong hop le" << endl;
    }
}
    return 0;
}

