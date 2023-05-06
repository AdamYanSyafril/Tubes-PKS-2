#include<iostream>
using namespace std;

int main () {
    int i, jumlah_ruangan, frekuensi[100];  
    string nama_ruangan[100], status[100];
    
    cout << "Jumlah ruangan uji = ";
    cin >> jumlah_ruangan;
    
    for (i = 0; i < jumlah_ruangan; i++) {
		cout << endl;
		
		cout << "Ruangan uji ke-" << i+1 <<endl;
		cout << "Masukkan nama ruangan uji = ";
		cin >> nama_ruangan[i];
		getline (cin, nama_ruangan[i]);
		cout << "Frekuensi maksimal yang diharapkan akan terdengar pada ruangan tersebut = ";
		cin >> frekuensi[i];
		
		if (frekuensi[i] > 5000) {
		 	status[i] = "Perlu dilakukan penyesuaian dengan menambahkan material kedap suara";
		} else if (frekuensi[i] < 1000) {
			status[i] = "Perlu dilakukan penyesuaian dengan mengurangi material kedap suara";
		} else {
		    status[i] = "Perlu dilakukan penyesuaian antara ukuran ruangan dengan frekuensi maksimalnya";
		}
	}
	
	cout << endl;
	
	for (i = 0; i < jumlah_ruangan; i++) {
	    cout << "Ruangan uji ke-" << i+1 << " yaitu " << nama_ruangan[i] << ", " << status[i] << endl;
	}
	
	return 0;
}
