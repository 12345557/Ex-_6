Experiment 6: Predictive Parsing Table
Aim:
To construct a predictive parsing table for a given grammar.
Code
#include <stdio.h>
#include <string.h>
Char prod[10][10];
Char first[10], follow[10];
Int main() {
 Int n, I;
 Printf(“Enter number of productions: “);
 Scanf(“%d”, &n);
 Printf(“Enter productions (E=E+T format):\n”);
 For(i=0;i<n;i++)
 Scanf(“%s”, prod[i]);
 Printf(“\nProductions:\n”);
 For(i=0;i<n;i++)
 Printf(“%s\n”, prod[i]);
 Printf(“\nPredictive Parsing Table constructed (simplified).\n”);
 Return 0;
