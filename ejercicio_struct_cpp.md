//Crear un programa que pida ados personas sus respectivos nombres y apellidos, dar 2 puntajes a estos, y para finalizar envie en output los datos

#include<iostream>


using namespace std;

struct classe {
	char cog[40];
	char nome[40];
	int voto1;
	int voto2;
};


int main() {
	struct classe quartao[2];
	int i;

	for (i = 0; i < 2; i++) {
		cout << "Inserisci il cognome: "; cin >> quartao[i].cog;
		cout << "Inserisci il nome: "; cin >> quartao[i].nome;
		cout << "Inserisci il voto 1: "; cin >> quartao[i].voto1;
		cout << "Inseriscil il voto 2: "; cin >> quartao[i].voto2;
	}

	for (i = 0; i < 2; i++) {
		cout << "\nIl cogome del " << i + 1 << " studente: " << quartao->cog<<endl;
		cout << "\nIl nome del " << i + 1 << " studente: " << quartao->nome<<endl;
		cout << "\nIl voto1 e: " << quartao->voto1<<endl;
		cout << "\nIl voto 2 e: " << quartao->voto2;

	}





	return 0; 
}
