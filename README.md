#include "iostream"

using namespace std;

int main(){

	string NPM;
	string Tanggal_lahir;
	string Bulan_lahir;
	string Tahun_lahir;
	
	
	getline(cin,NPM);
	getline(cin,Tanggal_lahir);
	getline(cin,Bulan_lahir);
	getline(cin,Tahun_lahir);
	cout<<""<<endl;
	
	
	cout<<"username : "<< NPM << endl;
	cout<<"Password : "<< Tanggal_lahir << " " << Bulan_lahir << " " << Tahun_lahir << endl;
}
