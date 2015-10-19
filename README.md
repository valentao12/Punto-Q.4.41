# Punto-Q.4.41
Further Analysis
Q.5.41 Load and run the program of Example 5.7.
clf

>> Beta = linspace(0,2*pi,50);

>> R1=10*sin(Beta);

>> R2 =-R1;

>> R3 =10*cos(Beta);

>> R4 =-R3;

>> polar (Beta,R1);

>> hold on

>> polar (Beta,R2);

>> hold on

>> polar (Beta,R3);

>> hold on

>> polar (Beta,R4);

>> title (‘[10sin(Beta), -10sin(Beta), 10cos(Beta), -10cos(Beta)] vs Rs, 

onone polar graph’)
