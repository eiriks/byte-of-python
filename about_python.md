# Om Python
<!-- # About Python -->

Python er et av de sjeldene programmeringsspråkene som vi kan si at er
både enkelt _og_ kraftig. Du vil bli overrasket over hvordan det er
mulig å konsentere seg om løsninger på oppgavene dine i stedet for å
fokusere på struktur og syntaks til programmeringsspråket.

<!-- Python is one of those rare languages which can claim to be both -->
<!-- _simple_ and _powerful_.  You will find yourself pleasantly surprised -->
<!-- to see how easy it is to concentrate on the solution to the problem -->
<!-- rather than the syntax and structure of the language you are -->
<!-- programming in. -->

Den offisielle introduksjonen til Python lyder (oversatt til norsk):

<!-- The official introduction to Python is: -->

> Python er et kraftig programmeringsspråk som er enkelt å
> lære. Språket bringer med seg effektive høynivås datastrukturer og
> en enkel, men effektiv tilnærming til objektorientert
> programmering. Pythons elegante syntaks og dynamiske typesystem,
> sammen med hvordan Python blir tolket, gjør språket til ideelt for
> skripting og rask programvareutvikling på de fleste platformer.

<!-- > Python is an easy to learn, powerful programming language. It has -->
<!-- > efficient high-level data structures and a simple but effective -->
<!-- > approach to object-oriented programming. Python's elegant syntax and -->
<!-- > dynamic typing, together with its interpreted nature, make it an -->
<!-- > ideal language for scripting and rapid application development in -->
<!-- > many areas on most platforms. -->

Uten kontekst så går mange av de ordene inn det ene øret og ut det
andre. Les videre så skal vi prøve å forklare.


<!-- I will discuss most of these features in more detail in the next -->
<!-- section. -->

## Historien bak navnet
<!-- ## Story behind the name -->

Guido van Rossum, oppfinneren av Python, kalte språket opp etter TV
programmet "Monty Python's Flying Circus". Det er ikke slik at han er
veldig glad i slanger som bruker den lange kroppen sin til å kveile
seg rundt andre dyr for så å kvele dem til døde.

<!-- Guido van Rossum, the creator of the Python language, named the -->
<!-- language after the BBC show "Monty Python's Flying Circus". He doesn't -->
<!-- particularly like snakes that kill animals for food by winding their -->
<!-- long bodies around them and crushing them. -->

## Hva gjør Python spesielt?
<!-- ## Features of Python -->

### Enkelt
<!-- ### Simple -->

Python er et enkelt og minimalistiskt språk. Når man leser et godt
utformet Python program så føles det nesten som å lese engelsk. Dog,
ganske strengt skrevet engelsk. Dette gjør at Python føles mer som
psudo-kode istedenfor maskininstrukser og er kanskje den største
styrken til Python. Det gjør at det er mulig å konsentere seg mer og
løsningene på oppgaven man har satt seg istendenfor å sloss hvordan
man skriver språket.

<!-- Python is a simple and minimalistic language. Reading a good Python -->
<!-- program feels almost like reading English, although very strict -->
<!-- English! This pseudo-code nature of Python is one of its greatest -->
<!-- strengths. It allows you to concentrate on the solution to the problem -->
<!-- rather than the language itself. -->

### Lett å lære
<!-- ### Easy to Learn -->

Som du kommer til å så er Python veldig lett å komme i gang med. Som
vi allerede har nevnt (flere ganger), så har Python en utrolig enkel
syntaks.

<!-- As you will see, Python is extremely easy to get started with. Python -->
<!-- has an extraordinarily simple syntax, as already mentioned. -->


### Fri og åpen kildekode
<!-- ### Free and Open Source -->

Python er et eksempel på et program som har fri og åpen
kildekode. Enkelt sagt så betyr det at du kan kopiere og gi fra deg så
mange kopier av Python du vil. Det er ingen som kan stoppe deg fra å
lese kildekoden eller gjøre endringer på den eller bruke deler av
Python til å laget et nytt program. Fri og åpen kildekode er basert på
å skape et samfunn som deler kunnskap. Dette er en av ideene bak
Python som gjør språket så bra: Det har vokst opp et sammfunn rundt
Python som kontinuerlig oppdaterer og forbedrer språket til fordel for
alle.

<!-- Python is an example of a _FLOSS_ (Free/Libré and Open Source -->
<!-- Software). In simple terms, you can freely distribute copies of this -->
<!-- software, read its source code, make changes to it, and use pieces of -->
<!-- it in new free programs. FLOSS is based on the concept of a community -->
<!-- which shares knowledge. This is one of the reasons why Python is so -->
<!-- good - it has been created and is constantly improved by a community -->
<!-- who just want to see a better Python. -->

### Et høynivås språk
<!-- ### High-level Language -->

Vi tenker på Python som et høynivå programmeringsspråk fordi vi ikke
trenger å ta høyde for hvordan vi håndterer bruken av minne eller
andre lavnivås detaljer.

<!-- When you write programs in Python, you never need to bother about the -->
<!-- low-level details such as managing the memory used by your program, -->
<!-- etc. -->

### Tilgjengelighet

På grunn av at Python er åpen kildekode så har Python blitt gjort
tilgjengelig på mange platformer. Alle Python programmene du skriver
vil kunne virke på alle platformer som Python kjører på uten at det
trengs endringer så lenge du har vært forsiktig med å ikke bruke
platform-avhengige funksjoner.

<!-- Due to its open-source nature, Python has been ported to (i.e. changed -->
<!-- to make it work on) many platforms. All your Python programs can work -->
<!-- on any of these platforms without requiring any changes at all if you -->
<!-- are careful enough to avoid any system-dependent features. -->

Du kan kjøre Python på GNU/Linux, Windows, FreeBSD, Macintosh,
Solaris, OS/2, Amiga, AROS, AS/400, BeOS, OS/390, z/OS, Palm OS, QNX,
VMS, Psion, Acorn RISC OS, VxWorks, PlayStation, Sharp Zaurus, Windows
CE og PocketPC!

<!-- You can use Python on GNU/Linux, Windows, FreeBSD, Macintosh, Solaris, -->
<!-- OS/2, Amiga, AROS, AS/400, BeOS, OS/390, z/OS, Palm OS, QNX, VMS, -->
<!-- Psion, Acorn RISC OS, VxWorks, PlayStation, Sharp Zaurus, Windows CE -->
<!-- and PocketPC! -->

Der fins til og med platformer som [Kivy](http://kivy.org) som gjør
det mulig å lage spill som ikke bare virker på datamaskinen din, men
også på iPhone, iPad og Android.

<!-- You can even use a platform like [Kivy](http://kivy.org) to create games for your computer _and_ for iPhone, iPad, and Android. -->

### Tolket
<!-- ### Interpreted -->

Å si at et språk et tolket krever litt forklaring.

<!-- This requires a bit of explanation. -->

Et program som er skrevet i et kompilert språk, slik som C eller C\++
blir konvertert fra kildekoden det er skrevet i til et annet språk som
datamaskinen din forstår(, binærkode, eller 1'er og 0'er,) ved hjelp
av en kompilator. Når du kjører programmet så kopieres programmet fra
hardisk'en over til minnet og det begynner å kjøre.

<!-- A program written in a compiled language like C or C\++ is converted -->
<!-- from the source language i.e. C or C++ into a language that is spoken -->
<!-- by your computer (binary code i.e. 0s and 1s) using a compiler with -->
<!-- various flags and options. When you run the program, the linker/loader -->
<!-- software copies the program from hard disk to memory and starts -->
<!-- running it. -->

Med et språk som Python så er det ikke nødvendig å kompilere
kildekoden til binærkode. Kildekoden leses og kjøres _direkte_.
Internt så konverterer Python kildekoden til et mellomliggende format
kalt bytekode som så blir oversatt til en binærkode som datamaskinen
din forstår som så kjører programmet. Dette høres kanskje komplisert
ut, men gjør det faktisk slik at Python er enklere å bruke. Dette er
fordi du ikke trenger å tenke på om de riktige bibliotekene er lenket
og lastet, etc. Det gjør også at Python programmene dine blir mer
tilgjengelige, siden alt andre trenger for å kjøre programmet ditt er
en kopi av kildekoden.

<!-- Python, on the other hand, does not need compilation to binary. You -->
<!-- just _run_ the program directly from the source code. Internally, -->
<!-- Python converts the source code into an intermediate form called -->
<!-- bytecodes and then translates this into the native language of your -->
<!-- computer and then runs it. All this, actually, makes using Python much -->
<!-- easier since you don't have to worry about compiling the program, -->
<!-- making sure that the proper libraries are linked and loaded, etc. This -->
<!-- also makes your Python programs much more portable, since you can just -->
<!-- copy your Python program onto another computer and it just works! -->

### Objektorientert
<!-- ### Object Oriented -->

Python støtter prosedyrell programmering så vell som objektorientert
programmering. I prosedyrelle språk så bygger man programmet rundt
prosedyrer og funksjonener som er lite annet enn gjennbrukbare små
kodesnutter. I objektorienterte språk så er programmene bygget rundt
konseptuelle objekter som kombinerer informasjon og
funksjonalitet. Python har en veldig kraftig, men enkel, måte å
programmere objektorientert på, spesielt sammenlignet med tyngre sprak
som C++ og Java.

<!-- Python supports procedure-oriented programming as well as -->
<!-- object-oriented programming. In _procedure-oriented_ languages, the -->
<!-- program is built around procedures or functions which are nothing but -->
<!-- reusable pieces of programs. In _object-oriented_ languages, the -->
<!-- program is built around objects which combine data and -->
<!-- functionality. Python has a very powerful but simplistic way of doing -->
<!-- OOP, especially when compared to big languages like C++ or Java. -->

### Utvidbart
<!-- ### Extensible -->

Hvis du virkelig trenger at en kritisk del av koden kjører veldig fort
eller vil at deler av algoritmen du skriver ikke skal være åpen for
andre, så kan du skrive deler av programmet ditt i C eller C\++ for så
å bruke den kompilerte binærkoden fra Python programmet ditt.

<!-- If you need a critical piece of code to run very fast or want to have -->
<!-- some piece of algorithm not to be open, you can code that part of your -->
<!-- program in C or C\++ and then use it from your Python program. -->

### Inbyggbart
<!-- ### Embeddable -->

Det er også mulig å bruke Python som en del av et C/C\++ program for å
gi skriptemuligheter til brukerene av programmet; å bygge det inn i
funksjonaliteten av programmet


<!-- You can embed Python within your C/C\++ programs to give _scripting_ -->
<!-- capabilities for your program's users. -->

### Omfattende bibliotek

Python sitt standard bibliotek er stort. Der kan du finne kode som kan
hjelpe deg med regulære uttrykk, dokumentasjonsgenerering,
enhetstesting, tråding, databaser, nettlesere, CGI, FTP, e-post, XML,
XML-RPC, HTML, WAV filer, kryptografi, grafiske brukergrensesnitt og
andre systemavhengige ting. Det er ikke nødvendig å vite hva alt dette
er, men det kan spare deg for masse tid neste gang du skal begynne på
en oppgave å sjekke om standard biblioteket allerede implementerer noe
av det du skal gjøre. Husk på at alt dette alltid er tilgjengelig der
Python er installert. Dette er _Batterier Inkludert_ filosofien bak
Python.

<!-- The Python Standard Library is huge indeed. It can help you do various -->
<!-- things involving regular expressions,documentation generation, unit -->
<!-- testing, threading, databases, web browsers, CGI, FTP, email, XML, -->
<!-- XML-RPC, HTML, WAV files, cryptography, GUI (graphical user -->
<!-- interfaces), and other system-dependent stuff. Remember, all this is -->
<!-- always available wherever Python is installed. This is called the -->
<!-- _Batteries Included_ philosophy of Python. -->

Utenom standard biblioteket så er det mange biblioteker tilgjengelig i
[Python Package Index](http://pypi.python.org/pypi).

<!-- Besides the standard library, there are various other high-quality -->
<!-- libraries which you can find at the -->
<!-- [Python Package Index](http://pypi.python.org/pypi). -->


### Sammendrag
<!-- ### Summary -->

Python er et spennende og kraftig programmeringssprak. Utviklerene har
virkelig gjort de riktige avveiningene mellom ytelse og funksjonalitet
som gjør det både gøy og enkelt å skrive program i Python.

<!-- Python is indeed an exciting and powerful language. It has the right -->
<!-- combination of performance and features that make writing programs in -->
<!-- Python both fun and easy. -->

## Python 3 kontra 2
<!-- ## Python 3 versus 2 -->

Det er ikke nødvendig å lese denne seksjonen med mindre du er
interessert i forskjelligen mellom "Python versjon 2" og "Python
versjon 3", bare husk på å sjekke hvike versjon du bruker. Denne boken
er skrevet for Python versjon 3.

<!-- You can ignore this section if you're not interested in the difference -->
<!-- between "Python version 2" and "Python version 3". But please do be -->
<!-- aware of which version you are using. This book is written for Python -->
<!-- version 3. -->

Det er verdt å vite at når du har lært å bruke en versjon så skal det
være lett å lære seg å programmere i den andre. Det som er vanskelig
er å lære seg programmering og å få en god forståelse for de
grunnleggende elementene av Python i seg selv. Det er målet som vi
setter oss for denne boken, og når du har nådd det målet så skal du
lett kunne ta i bruk både Python 3 og Python 2 om situasjonen krever det.

<!-- Remember that once you have properly understood and learn to use one -->
<!-- version, you can easily learn the differences and use the other -->
<!-- one. The hard part is learning programming and understanding the -->
<!-- basics of Python language itself. That is our goal in this book, and -->
<!-- once you have achieved that goal, you can easily use Python 2 or -->
<!-- Python 3 depending on your situation. -->

Hvis du vil ha en detaljert oversikt over hva forskjellen er mellom de
2 forskjellige versjonene så kan du besøde de følgende lenkene:

<!-- For details on differences between Python 2 and Python 3, see: -->

- [The future of Python 2](http://lwn.net/Articles/547191/)
- [Porting Python 2 Code to Python 3](https://docs.python.org/3/howto/pyporting.html)
- [Writing code that runs under both Python2 and 3](https://wiki.python.org/moin/PortingToPy3k/BilingualQuickRef)
- [Supporting Python 3: An in-depth guide](http://python3porting.com)

## Hva andre programmere sier
<!-- ## What Programmers Say -->

Det kan være at du finner det interessant hva noen av de virkelig
store "hackerene" som ESR sier om Python:

<!-- You may find it interesting to read what great hackers like ESR have -->
<!-- to say about Python: -->

- _Eric S. Raymond_ er forfatteren bak "The Cathedral and the Bazaar"
  og fant opp uttrykket _Open Source_. Han sier at
  [Python har blitt favoritt språket hans](http://www.python.org/about/success/esr/).
- _Bruce Eckel_ er forfatteren bak bøkene "Thinking in Java" og
  "Thinking in C++". Han sier at det ikke fins et programmeringsspråk
  som har gjort ham mer produktiv enn Python. Han sier at Python
  muligens er det eneste språket som fokuserer på gjør ting enklere
  for programmereren. Du kan lese
  [hele intervjuet](http://www.artima.com/intv/aboutme.html) hvis du
  vil ha flere detaljer.
- _Peter Norvig_ er en kjent kunstig intelligens utvikler og direktør
  for søkekvalitet hos Google. Han sier at
  [å skrive Python er som å skrive i pseudokode](https://news.ycombinator.com/item?id=1803815)
  og at Python alltid har vært en itegral del av Google. Hvis du ser
  på
  [jobbutlysninger fra Google](http://www.google.com/jobs/index.html)
  så er Python et krav for programmerere.

<!-- - _Eric S. Raymond_ is the author of "The Cathedral and the Bazaar" and is also the person who coined the term _Open Source_. He says that [Python has become his favorite programming language](http://www.python.org/about/success/esr/). This article was the real inspiration for my first brush with Python. -->
<!-- - _Bruce Eckel_ is the author of the famous 'Thinking in Java' and 'Thinking in C++' books. He says that no language has made him more productive than Python. He says that Python is perhaps the only language that focuses on making things easier for the programmer. Read the [complete interview](http://www.artima.com/intv/aboutme.html) for more details. -->
<!-- - _Peter Norvig_ is a well-known Lisp author and Director of Search Quality at Google (thanks to Guido van Rossum for pointing that out). He says that [writing Python is like writing in pseudocode](https://news.ycombinator.com/item?id=1803815). He says that Python has always been an integral part of Google. You can actually verify this statement by looking at the [Google Jobs](http://www.google.com/jobs/index.html) page which lists Python knowledge as a requirement for software engineers. -->
