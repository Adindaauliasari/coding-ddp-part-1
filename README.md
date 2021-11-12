#include <iostream>
using namespace std;
int main(){
	
	/* Nama  : Adinda aulia sari
	   NPM   : 2117051018
	   Kelas : B
	*/
	
	//string//
	string NPM;
	string Tanggal_lahir;
	string Bulan_lahir;
	string Tahun_lahir;
	
	//input//
	getline(cin,NPM);
	getline(cin,Tanggal_lahir);
	getline(cin,Bulan_lahir);
	getline(cin,Tahun_lahir);
	cout<<""<<endl;
	
	//output//
	cout<<"username : "<< NPM << endl;
	cout<<"Password : "<< Tanggal_lahir << " " << Bulan_lahir << " " << Tahun_lahir << endl;
	return 0;
}
