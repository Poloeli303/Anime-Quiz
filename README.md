#include<iostream>
using namespace std;

int main() {
	//variables to hold onto each princess' score:
	int Naruto = 0;
	int Saitama = 0;
	int Emma = 0;
	int Natsu = 0;
	int Eren = 0;
	int Kirito = 0;
	char choice; //variable to hold user input

	cout << "Welcome to the anime quiz!" << endl;

	//question 1
	cout << "What's your favorite animal? (f)ox, (m)osquito, or (g)iraffe, or (d)ragon, or (t)itan, or (w)olf?" << endl;
	cin >> choice;
	if (choice == 'f')
		Naruto++;
	else if (choice == 'm')
		Saitama++;
	else if (choice == 'g')
		Emma++;
	else if (choice == 'd')
		Natsu++;
	else if (choice == 't')
		Eren++;
	else if (choice == 'w')
		Kirito++;
	else
		cout << "not an option, dummy" << endl;

	cout << "Whats your favorite color? (o)range, (y)ellow, (w)hite, (p)ink, (g)reen, (b)lack?" << endl;
	cin >> choice;
	if (choice == 'o')
		Naruto++;
	else if (choice == 'y')
		Saitama++;
	else if (choice == 'w')
		Emma++;
	else if (choice == 'p')
		Natsu++;
	else if (choice == 'g')
		Eren++;
	else if (choice == 'b')
		Kirito++;
	else
		cout << "Why would you choose anything else??" << endl;

	cout << "Whats your favorite food? (r)amen, (l)obster, (b)roths, (f)ire, (m)eat, (b)read?" << endl;
	cin >> choice;
	if (choice == 'r')
		Naruto++;
	else if (choice == 'l')
		Saitama++;
	else if (choice == 'b')
		Emma++;
	else if (choice == 'f')
		Natsu++;
	else if (choice == 'm')
		Eren++;
	else if (choice == 'b')
		Kirito++;
	else
		cout << "You chose something before why stop now??" << endl;

	//more questions go here!

	//check which princess has the biggest score
	//the symbol "&&" means AND
	if (Naruto >= Saitama && Naruto >= Emma && Naruto >= Natsu && Naruto >= Eren && Naruto >= Kirito)
		cout << "You'll be hokage too one day! Believe it!! you got Naruto" << endl;
	else if (Saitama >= Naruto && Saitama >= Emma && Saitama >= Natsu && Saitama >= Eren && Saitama >= Kirito)
		cout << "Ok ... you got Saitama" << endl;
	else if (Emma >= Naruto && Emma >= Saitama && Emma >= Natsu && Emma >= Eren && Emma >= Kirito)
		cout << "I may have lost my heart but not my self control ... You got Emma" << endl;
	else if (Natsu >= Naruto && Natsu >= Saitama && Natsu >= Emma && Natsu >= Eren && Natsu >= Kirito)
		cout << "Im all fired up! you got Natsu" << endl;
	else if (Eren >= Naruto && Eren >= Saitama && Eren >= Emma && Eren >= Natsu && Eren >= Kirito)
		cout << "Im gonna destroy them! you got Eren" << endl;
	else if (Kirito >= Naruto && Kirito >= Saitama && Kirito >= Emma && Kirito >= Natsu && Kirito >= Eren)
		cout << "Levels are just numbers ... you got Kirito" << endl;


}
