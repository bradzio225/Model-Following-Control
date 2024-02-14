# Model-Following-Control
Celem projektu było zamodelowanie układu ze strukturą MFC i obiektem 
wieloinercyjnym G z zadawanym skokowym sygnałem referencyjnym r i skokowym 
sygnałem zakłócenia na wyjściu z. W zadaniu należało wykorzystać poniższą 
strukturę MFC:


W projekcie przy pomocy dekonwolucji należało zidentyfikować kształt 
charakterystyki impulsowej g(t) oraz skokowej h(t). Następnie na podstawie 
wyznaczonej charakterystyki skokowej przy pomocy dwupunktowej metody 
Strejca przeprowadziliśmy identyfikację parametrów obiektu dobierając rząd, 
opóźnienie oraz stałą czasową.  
W oparciu o model Strejca został dobrany regulator główny RM. Regulator od 
zakłócenia RK został dobrany przy pomocy funkcji AutoTuningu dostępnej w 
pakiecie Matlab/Simulink.
