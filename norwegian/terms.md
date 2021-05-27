## Programmeringsuttrykk på norsk

Denne listen er et forsøk på å berike norske software-utvikleres norske vokabular.
Den er også tenkt å brukes som supplement i undervisning for å gi studenter en referanse å bruke når foreleser bruker ukjente ord og uttrykk.

Noen uttrykk i denne listen er bevisst beholdt på engelsk.
Disse uttrykkene er forsøkt linket til norske utgaver som opprinnelig forfatter ikke tror vil bli en del av språket til programmerere. Flere av disse uttrykkene er meget tvetydige på norsk. De er allikevel forsøkt å gjøre entydige i forhold til det engelske uttrykket ved å konkretisere i paragrafer. Eks. [Grensesnitt (programmering)](#grensnitt-programmering) for [Interface](#interface).

God fornorskelse!

#### Abstrakt klasse
_Abstract class_  
En [klasse](#klasse) som må arves for å kunne [instansieres](#instansiere). Brukes typisk for å dele grunnfunksjonalitet mellom arvede klasser.

#### Abstraksjon
_Abstraction_  
Klasse eller [_interface_](#interface) som beskriver grensesnittet til en eller flere [konkrete klasser](#konkret-klasse).

#### Algoritme
_Algorithm_  
Sett av [instrukser](#instruks) som sammen gir et ønsket resultat eller utfall.

#### Allokere
_Allocating_  
Sette av plass i minne. Mest brukt i forbindelse med objekter, men gjelder også for tabeller og andre strukturer. 

#### Bytecode
Synonum: _intermediate code_   
Binært mellomformat som er maskinuavhenging, og ikke kan kjøres direkte av et operativsystem. Kjøring av slik kode krever 
et passende [kjøremiljø](#kjøremiljø).

#### Felt (klasse)
_Field_  
En [variabel](#variabel) som tilhører en [klasse](#klasse). Kan være [privat](#privat), [beskyttet](#beskyttet) (protected) eller [offentlig](#offentlig) (public).  
Felt på [klasser](#klasse) kan enten være en [instansvariabel](#instansvariabel) eller en [statisk variabel](#statis-variabel)

#### Felt (database)
Se [kolonne](#kolonne)

#### Funksjon
_Function_  
Navngitt [algoritme](#algoritme) som kan kjøres en eller flere ganger ved å "kalle funksjonen".  
En funksjon _kan_ få ett eller flere [parametere](#parameter) send med i et "kall".  
En funksjon _kan_ returnere ett eller flere resultater. Typisk ett, men gjerne en [datastruktur](#datastruktur).

#### Grensesnitt (brukergrensesnitt)
_User interface_

#### Grensnitt (programmering)
_Interface_  
Et sett av [funksjonssignaturer](#signatur-funksjon) en klasse kan implementere.  
En [klasse](#klasse) som [implementerer](#implementere) et _interface_ kan benyttes via det som en [abstraksjon](#abstraksjon) i stedet for den [konkrete klassen](#konkret-klasse).


#### Instansiere
_Instantiating_  
Synonym: _opprette_  
Benyttes for å indikere at _noe_ blir opprettet. I praksis vil dette si at at minne blir avsatt ([allokert](#allokere)) 
til et bestemt bruk. Den vanligste måten å benytte denne termen er _å instansiere en klasse_. I denne settingen betyr dette å
_opprette et objekt (ut fra en klassedefinisjon)_. Det er også mulig å benytte _å instansiere en tabell_, men denne
bruksmåten er ikke veldig utbredt. 

#### Interface
_Interface_  
Se [grensesnitt](#grensnitt-programmering).

#### Intermediate code
Se [bytecode](#bytecode)

#### Kjøremiljø
_Run time environment_   
I moderne programvareutvikling forstås dette til å være maskinavhengig tolker for [byte code](byte code). Typisk er
dette .NET og Java Virtual Machine.


#### Klasse
_Class_

#### Kompilere
_Compile_   
Oversette menneskelig lesbar programkode til maskinlesbar kode. Dette kan både bety at resultatet kan kjøres rett fra operativsystemet,
eller at resultatet ([byte code](#bytecode)) kan benyttes i et bestemt [kjøremiljø](#kjøremiljø). Det siste er vanlig for _.NET_ og _Java Virutal Machine_
baserte spårk.

#### Kolonne
_Column_  
I databaser kalles definisjonen av hvert felt [radene](#rad) kan ha en kolonne.

#### Konkret klasse
_Concrete class_

#### Konstant
_Constant_  
En ikke-redigerbar [variabel](#variabel)

#### Metode (klasse)
_Method_  
En [funksjon](#funksjon) som tilhører en klasse. Kan være privat, beskyttet (beskyttet) eller offentlig (public).

#### Privat (klasse, felt, metode)
_Private_

#### Rad (database)
_Row_

#### Signatur (funksjon)
_signature_  
Delen av en funksjon som beskriver [returtype](#returtype), navn og [argumenter](#argument)


#### Transpilere
_transpile_    
Oversette, eller tranformere, kode fra ett programmeringsspråk til et annet. Kjente eksempler på dette er transpilering av 
_TypeScript_ eller _CoffeScript_ til _JavaScript_. Må ikke misforstås med [Kompilering](Kompilere).

#### Variabel
_Variable_  
