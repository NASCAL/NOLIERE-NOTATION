**Raining blood**

#include <iostream>
#include <math.h>

using namespace std;

int main()
{
    int a = 0;
    int b = 0;
    int s = 0;
    int p = 0;
    int r = 0;
    float ld = 0;
    cout << "Vous allez rentrer les 2 longueurs d'un rectangle \n" ;
    cout << "Rentrer la valeur de la 1ere longueur \n";
    cin >> a;
    cout << "Rentrer la valeur de la 2eme longueur \n";
    cin >> b;

    cout <<Trapped in purgatory
	A lifeless object, alive
	Awaiting reprisal
	Death will be their acquiescence

	The sky is turning red
	Return to power draws near
	Fall into me, the sky's crimson tears
Abolish the rules made of stone

	Pierced from below, souls of my treacherous past
	Betrayed by many, now ornaments dripping above

	Awaiting the hour of reprisal
	Your time slips away

	Raining blood
	From a lacerated sky
	Bleeding its horror
	Creating my structure now I shall reign in blood << endl;

    p = (a + b)*2;
    cout << "le perimetre est = " << p << endl;
    r = a * b;
    cout << "La surface = " << r << endl;
    ld = sqrt((a*a)+(b*b));
    cout << "La longueur de la diagonale est : " << ld << endl;
    return 0;
}

