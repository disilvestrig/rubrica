#include <iostream>
#include <string>
#include <list>
#include <algorithm>
#include <process.h>

using namespace std;

int main () {
	cout << "Hai aperto la rubrica \n" ;
	list <string> nomi ;
	list <string> cognomi ;
	list <int> numeri ;
	list <int> :: iterator p ;
	char alphabet[24] ;
	string res,nome,cognome,check,stop,check2,check3 ;
	int len , numero;
	len = 0; 
    res = " ";
	
	while (res != "1"){
		cout << "\n Quale funzione vuoi utilizzare ? \n1) Aggiungi contatto\n2) Visualizza rubrica \n3) Ricerca contatto\n";
		cin >> res ;
		if (res == "1" ){
		
		cout << "\n Inserisci nome \n";
		cin >> nome ;
		nomi.push_back(nome) ;
		cout << "\n Inserisci cognome \n";
		cin >> cognome ;
		cognomi.push_back(cognome);
		cout << "\n Inserisci numero \n";
		cout << "+39 ";
		cin >> numero;
		 
		numeri.push_back(numero);
	    len ++ ;
		}

	    if (res == "2"){
	       for (int i = 0;i<len; i ++){
	       	cout << nomi.back() << " ";
	       	nomi.push_front(nomi.back());
	       	nomi.pop_back();
	       	cout << cognomi.back() << " : ";
	       	cognomi.push_front(cognomi.back());
	       	cognomi.pop_back();
	       	cout <<"+39 "<< numeri.back() << "\n";
	       	numeri.push_front(numeri.back());
	       	numeri.pop_back();
		   }}
		if (res == "3"){
			cout << "\nChe tipo di ricerca vuoi effettuare ( 1. Nome, 2. Cognome, 3. Numero ) \n";
			cin >> res;
			if (res == "1"){
				cout << "Inserisci nome \n";
				cin >> check;
				for (int i = 0;i<len; i ++){
					check2 = nomi.back();
	       	        if (check2 == check){
	       	        	cout << nomi.back() << " ";
	       	        	cout << cognomi.back() << " : ";
	       	        	cout <<"+39 "<< numeri.back() << "\n";
					   }
	       	        nomi.push_front(nomi.back());
	       	        nomi.pop_back();
	       	        cognomi.push_front(cognomi.back());
	       	        cognomi.pop_back();
	       	        numeri.push_front(numeri.back());
	       	        numeri.pop_back();}}
	        if (res == "2"){
	        	cout << "Inserisci cognome\n" ;
	        	cin >> check ;
	        	for (int i = 0;i<len; i ++){
					check2 = cognomi.back();
	       	        if (check2 == check){
	       	        	cout << nomi.back() << " ";
	       	        	cout << cognomi.back() << " : ";
	       	        	cout <<"+39 "<< numeri.back() << "\n";
					   }
	       	        nomi.push_front(nomi.back());
	       	        nomi.pop_back();
	       	        cognomi.push_front(cognomi.back());
	       	        cognomi.pop_back();
	       	        numeri.push_front(numeri.back());
	       	        numeri.pop_back();}}
	       	if (res == "3"){
	        	cout << "Inserisci numero\n" ;
	        	cin >> check ;
	        	for (int i = 0;i<len; i ++){
					check2 = numeri.back();
	       	        if (check2 == check){
	       	        	cout << nomi.back() << " ";
	       	        	cout << cognomi.back() << " : ";
	       	        	cout <<"+39 "<< numeri.back() << "\n";
					   }
	       	        nomi.push_front(nomi.back());
	       	        nomi.pop_back();
	       	        cognomi.push_front(cognomi.back());
	       	        cognomi.pop_back();
	       	        numeri.push_front(numeri.back());
	       	        numeri.pop_back();}

			}
		}
		cout << "\nVuoi chiudere la rubrica ? digita 1 per sì o 2 per no >>> " ;
	    cin >> res ;
		system("cls");}

}
