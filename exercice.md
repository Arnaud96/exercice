# exercice

#include <stdio.h>
#include <stdlib.h>

#define PI 3.14159265359

int main(int argc, char* argv[])
{
	int taille_cote_carre = 0;
	int surface = 0;
	int rayon = 0;
	
	printf("Saisir la taille du cote du carre\n");
	scanf("%d",&taille_cote_carre);
	
	surface = taille_cote_carre * taille_cote_carre;
	
	rayon = taille_cote_carre / 2;
	
	printf("voici la surface : [%d] voici le rayon : [%d]",surface, rayon);
	
	return 0;
}
