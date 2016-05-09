<!-- # First Steps -->
# Første skritt

<!-- We will now see how to run a traditional 'Hello World' program in Python. This will teach you how to write, save and run Python programs.

There are two ways of using Python to run your program - using the interactive interpreter prompt or using a source file. We will now see how to use both of these methods. -->
Vi skal nå se hvordan vi kjører et tradisjonellt 'Hello World'-program i Python. Dette vil lære deg å skrive, lagre og kjøre Pythonprogrammer.

Det er to måter å bruke Python til å kjøre dine program, enten ved å bruke den interaktive fortolkeren (´interpreter´) eller ved å bruke en kildefil. Vi skal se hvordan begge disse metodene brukes.


<!-- ## Using The Interpreter Prompt -->
## Bruk av det tolkende promptet ???

<!-- Open the terminal in your operating system (as discussed previously in the [Installation](./installation.md#installation) chapter) and then open the Python prompt by typing `python3` and pressing `[enter]` key. -->
Åpne terminal i operativsystemet ditt (som diskutert tidligere i kappitellet om [instalasjon](./installation.md#installation)) og start Python promptet ved å skrive inn `python3` og trykke `[enter]` tasten.

<!-- Once you have started Python, you should see `>>>` where you can start typing stuff. This is called the _Python interpreter prompt_. -->
Når du har startet Python skal du se `>>>` hvor du kan starte å skrive inn ting. Dette heter _Python tolker promptet_.

<!-- At the Python interpreter prompt, type: -->
I Python tolker promptet, skriv:

```python
print("Hello World")
```

<!-- followed by the `[enter]` key. You should see the words `Hello World` printed to the screen. -->
etterfulgt av `[enter]` tasten. Du burde se ordene `Hello World` skrevet til skjermen.

<!-- Here is an example of what you should be seeing, when using a Mac OS X computer. The details about the Python software will differ based on your computer, but the part from the prompt (i.e. from `>>>` onwards) should be the same regardless of the operating system. -->
Her er et eksempel på hva du burde se, når man bruker en Mac OS X datamaskin. Detaljene om Python programvaren kan være litt ulikt basert på hva slags datamaskin du har, men den delen fra promptet (altså fra `>>>` og videre) skal være det samme uansett hva slags operativsystem du bruker.


<!-- The output should match pythonVersion variable in book.json -->
```python
> python3
Python 3.5.1 (default, Jan 14 2016, 06:54:11)
[GCC 4.2.1 Compatible Apple LLVM 7.0.2 (clang-700.1.81)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>> print("Hello World")
Hello World
```

<!-- Notice that Python gives you the output of the line immediately! What you just entered is a single Python _statement_. We use `print` to (unsurprisingly) print any value that you supply to it. Here, we are supplying the text `Hello World` and this is promptly printed to the screen. -->
Legg merke til at Python gir deg tilbakemelding øyeblikkelig! Det du just sente inn er et enkelt Python _statement_. Vi bruker `print` til å skrive ut en hvilkensomhelst verdi som du forer inn i print-statementet. Her putter vi inn teksten `Hello World` og dette skrive øyeblikkelig ut til skjermen.

<!-- ### How to Quit the Interpreter Prompt -->
### Hvordan avslutte det tolkende promptet

<!-- If you are using a GNU/Linux or OS X shell, you can exit the interpreter prompt by pressing `[ctrl + d]` or entering `exit()` (note: remember to include the parentheses, `()`) followed by the `[enter]` key. -->
Hvis du bruker et GNU/Linux eller OS X skall (shell), kan du lukke tolkeren ved å trykke `[ctrl + d]` eller skirve inn `exit()` (merk: husk på ta med parentesene, `()`) etter fulgt av `[enter]` teasten.

<!-- If you are using the Windows command prompt, press `[ctrl + z]` followed by the `[enter]` key. -->
Hvis du bruker Windows kommandolinje, trykk `[ctrl + z]` etter fulgt av `[enter]` tasten.

<!-- ## Choosing An Editor -->
## Valg av Editor

<!-- We cannot type out our program at the interpreter prompt every time we want to run something, so we have to save them in files and can run our programs any number of times. -->
Vi kan ikke skrive ting til det tolkende promptet hver gang vi ønsker å kjøre noe, så vi må lagre koden vår i filer som vi kan kjør igjen og igjen når det passer oss.

<!-- To create our Python source files, we need an editor software where you can type and save. A good programmer's editor will make your life easier in writing the source files. Hence, the choice of an editor is crucial indeed. You have to choose an editor as you would choose a car you would buy. A good editor will help you write Python programs easily, making your journey more comfortable and helps you reach your destination (achieve your goal) in a much faster and safer way. -->
For å lage Python filer med kildekode trenger vi en editor (redigeringsprogrammvare) til å skrive i og lagre. En bra editor for programmerere gjør det mye enklere å skrive kildefiler. Derfor er det viktig å finne en god editor. En god editor hjelper deg med å skrive Pythonprogrammer lettere, og gjør veien enklere og mer komfortabel på din reise mot målene dine, og du kommer dit raskere og tryggere med litt hjekp fra en bra editor.

<!-- One of the very basic requirements is _syntax highlighting_ where all the different parts of your Python program are colorized so that you can _see_ your program and visualize its running. -->
Et helt grunnleggende krav er _syntaks utheving_ (syntax highlighting) slik at de ulike delene av programmet ditt blir fargekodet slik at du kan _se_ programmet og se for deg hvordan det vil kjøre.

<!-- If you have no idea where to start, I would recommend using [PyCharm Educational Edition](https://www.jetbrains.com/pycharm-edu/) software which is available on Windows, Mac OS X and GNU/Linux. Details in the next section. -->
Hvis du ikke har noen idé om hvor du skal starte, så vil jeg anbefale at du bruker [PyCharm Educational Edition](https://www.jetbrains.com/pycharm-edu/) som er tilgjengelig for Windows, Mac OS X og GNU/Linux. Detaljer kommer i neste avsnitt.


<!-- If you are using Windows, *do not use Notepad* - it is a bad choice because it does not do syntax highlighting and also importantly it does not support indentation of the text which is very important in our case as we will see later. Good editors will automatically do this. -->
Hvis du bruker Windows, *ikke bruk Notisblokk (Notepad)* - det er et dårlig valg fordi det ikke har syntaks utheving og like viktig: det støtter ikke indentering (indrag) av teksten som er svært viktig i vår tilfelle. Det skal vi se nærmere på snart. Gode editorer gjør dette automatisk.

<!-- If you are an experienced programmer, then you must be already using [Vim](http://www.vim.org) or [Emacs](http://www.gnu.org/software/emacs/). Needless to say, these are two of the most powerful editors and you will benefit from using them to write your Python programs. I personally use both for most of my programs, and have even written an [entire book on Vim]({{ book.vimBookUrl }}). -->
Hvis du er en erfaren programmerer, så bruker du kanskje allerede [Vim](http://www.vim.org) eller [Emacs](http://www.gnu.org/software/emacs/).
Dette er to av de skraftigere editorene og du vil dra nytte av disse når du skriver Pythonprogrammer. Personlig bruker jeg begge disse til de fleste av mine programmer, og har til og med skrevet en [hel bok om Vim](http://vim.swaroopch.com/).


<!-- In case you are willing to take the time to learn Vim or Emacs, then I highly recommend that you do learn to use either of them as it will be very useful for you in the long run. However, as I mentioned before, beginners can start with PyCharm and focus the learning on Python rather than the editor at this moment. -->
Hvis du er villig til å ta deg tid til å lære Vim eller Emacs, så enbefaler jeg på det varmeste at du gjør det - det kommer til å lønne seg på sikt. Men, nybegynnere kan starte med PyCharm og fokusere på Python i stede for editoen i starten.


<!-- To reiterate, please choose a proper editor - it can make writing Python programs more fun and easy. -->
For å oppsummere: velg en passende editor - den kan gjøre det å skrive Pythonprogrammer både enklere og gøyere.

<!-- ## PyCharm {#pycharm} -->
## PyCharm<a name="pycharm"></a>

<!-- [PyCharm Educational Edition](https://www.jetbrains.com/pycharm-edu/) is a free editor which you can use for writing Python programs. -->
[PyCharm Educational Edition](https://www.jetbrains.com/pycharm-edu/) er en gratisk editor som du kan bruke til å skrive Pythonprogrammer.

<!-- When you open PyCharm, you'll see this, click on `Create New Project`: -->
Når du åpner PyCharm ser du dette, klikk på `Create New Project`:

![When you open PyCharm](./img/pycharm_open.png)

<!-- Select `Pure Python`: -->
Velg `Pure Python`:

![PyCharm New Project](./img/pycharm_create_new_project.png)

<!-- Change `untitled` to `helloworld` as the location of the project, you should see details similar to this: -->
Endre `untitled` til `helloworld` som lokasjonene til prosjektet, da burde du se detaljer omtrent som dette:

![PyCharm project details](./img/pycharm_create_new_project_pure_python.png)

<!-- Click the `Create` button. -->
Klikk på `Create`-knappen.

<!-- Right-click on the `helloworld` in the sidebar and select `New` -> `Python File`: -->
Høyreklikk på `helloworld` i sidemenyen og velg `New` -> `Python File`: -->

![PyCharm -> New -> Python File](./img/pycharm_new_python_file.png)

<!-- You will be asked to type the name, type `hello`: -->
Du vil bli spurt om å gi en navn, skriv `hello`: -->

![PyCharm New File dialog box](./img/pycharm_new_file_input.png)

<!-- You can now see a file opened for you: -->
Du kan nå se en åpen fil:

![PyCharm hello.py file](./img/pycharm_hello_open.png)

<!-- Delete the lines that are already present, and now type the following: -->
Slett linjene som allerede er der, og skriv inn det følgende:

<!-- TODO: Update screenshots for Python 3 -->

```python
print("hello world")
```
<!-- Now right-click on what you typed (without selecting the text), and click on `Run 'hello'`. -->
Høyreklikk på det du skrev (uten å markere teksten), og klikk på `Run 'hello'`.


![PyCharm Run 'hello'](./img/pycharm_run.png)

<!-- You should now see the output (what it prints) of your program: -->
Du bør nå se utskriften (output - det som printes fra print-statementet) av programmet ditt:

![PyCharm output](./img/pycharm_output.png)

<!-- Phew! That was quite a few steps to get started, but henceforth, every time we ask you to create a new file, remember to just right-click on `helloworld` on the left -> `New` -> `Python File` and continue the same steps to type and run as shown above. -->
Phew! Det vra ganske mange skritt for å komme i gang, men herfra, hver gang vi skal lage en ny fil, husk å høyreklikke på `helloworld`på venstresiden -> `New`-> `Python file`og fortsett på samme vis som vist over.


<!-- You can find more information about PyCharm in the [PyCharm Quickstart](https://www.jetbrains.com/pycharm-educational/quickstart/) page. -->
Du finner mer informasjon om PyCharm på [PyCharm Quickstart](https://www.jetbrains.com/pycharm-educational/quickstart/) siden.

## Vim

<!-- 1. Install [Vim](http://www.vim.org)
    * Mac OS X users should install `macvim` package via [HomeBrew](http://brew.sh/)
    * Windows users should download the "self-installing executable" from [Vim website](http://www.vim.org/download.php)
    * GNU/Linux users should get Vim from their distribution's software repositories, e.g. Debian and Ubuntu users can install the `vim` package.
2. Install [jedi-vim](https://github.com/davidhalter/jedi-vim) plugin for autocompletion.
3. Install corresponding `jedi` python package : `pip install -U jedi` -->
1. Installer [Vim](http://www.vim.org)
    * Mac OS X-brukere burde installere `macvim` pakken via [HomeBrew](http://brew.sh/)
    * Windows-brukere burde laste ned  det "selv-installerende eksekverbare" programmet fra [Vim website](http://www.vim.org/download.php)
    * GNU/Linux-brukere kan få Vim fra sine distribusjons programvare  nedlastings-senter, f.eks. kan Debian og Ubuntu-brukere  installere `vim` pakken.
2. Installer [jedi-vim](https://github.com/davidhalter/jedi-vim) innstikket for autofullføring.
3. Installer tilhørende `jedi` python pakke : `pip install -U jedi`

## Emacs

<!-- 1. Install [Emacs 24+](http://www.gnu.org/software/emacs/).
    * Mac OS X users should get Emacs from http://emacsformacosx.com
    * Windows users should get Emacs from http://ftp.gnu.org/gnu/emacs/windows/
    * GNU/Linux users should get Emacs from their distribution's software repositories, e.g. Debian and Ubuntu users can install the `emacs24` package.
2. Install [ELPY](https://github.com/jorgenschaefer/elpy/wiki) -->
1. Installer [Emacs 24+](http://www.gnu.org/software/emacs/).
    * Mac OS X-brukere kan laste ned Emacs fra http://emacsformacosx.com
    * Windows-brukere kan laste ned Emacs fra http://ftp.gnu.org/gnu/emacs/windows/
    * GNU/Linux-brukere kan få Emacs from their distribution's software repositories, f.eks. kan Debian og Ubuntu-brukere  installere `emacs24` pakken.
2. Installer [ELPY](https://github.com/jorgenschaefer/elpy/wiki)


<!-- ## Using A Source File -->
## Bruk av Kildefiler

<!-- Now let's get back to programming. There is a tradition that whenever you learn a new programming language, the first program that you write and run is the 'Hello World' program - all it does is just say 'Hello World' when you run it. As Simon Cozens[^1] says, it is the "traditional incantation to the programming gods to help you learn the language better." -->
Tilbake til programmering. Der er en tradisjon at når man lærer et nytt programmeringsspråk, så starter man med å skrivet et 'Hello World' (Hei Verden) program - et program som bare skriver ut 'Hello World' når du kjører det. Som Simon As Simon Cozens[^1] sier, det er er den tranidsjonelle hilsnen til programmeringsgudene for å be om god hjelp til å lære språket bedre.


<!-- Start your choice of editor, enter the following program and save it as `hello.py`. -->
Start din editor, skriv inn følgende program og lagre filen som `hello.py`.

<!-- If you are using PyCharm, we have already [discussed how to run from a source file](#pycharm). -->
Hvis du bruker PyCharm har vi allerede [diskutert hvordan man kjører en kildefil](#pycharm).

<!-- For other editors, open a new file `hello.py` and type this: -->
For andre editorer, opne en ny fil `hello.py`og skriv inn dette:

```python
print("hello world")
```

<!-- Where should you save the file? To any folder for which you know the location of the folder. If you
don't understand what that means, create a new folder and use that location to save and run all
your Python programs: -->
Hvor skal du lagre filen din? Jo, i en hvilken som helst folder som du vet hvor er. Hvis du ikke fårstår hva det betyr, lag en ny folder og bruk denne til å lagre og kjøre alle dine Pythonprogrammer:

- `/tmp/py` på Mac OS X
- `/tmp/py` på GNU/Linux
- `C:\\py` på Windows

<!-- To create the above folder (for the operating system you are using), use the `mkdir` command in the terminal, for example, `mkdir /tmp/py`. -->
For å lage folderen som vist over (for det operativsystemet du bruker), bruk `mkdir` kommandoen i terminalen, f.eks. `mkdir /tmp/py`.

<!-- IMPORTANT: Always ensure that you give it the file extension of `.py`, for example, `foo.py`. -->
VIKTIG: Sørg alltid for at du gir filene dine filendelsen `.py`, f.eks. `foo.py`.

<!-- To run your Python program: -->
Hvordan kjøre ditt Pythonprogram:

<!-- 1. Open a terminal window (see the previous [Installation](./installation.md#installation) chapter on how to do that) -->
1. Opne et terminalvindu (se forrige kapittel om  [Installering](./installation.md#installation) for detaljer)
<!-- 2. **C**hange **d**irectory to where you saved the file, for example, `cd /tmp/py` -->
2. **C**hange **d**irectory (endre folder) dit hvor du lagret filen, f.eks. `cd /tmp/py`
<!-- 3. Run the program by entering the command `python hello.py`. The output is as shown below. -->
3. Kjør programmet ved å skrive inn kommandoen `python hello.py`. Resultatet kan du se under.

```
$ python hello.py
hello world
```

![Screenshot of running program in terminal](./img/terminal_screenshot.png)

<!-- If you got the output as shown above, congratulations! - you have successfully run your first Python program. You have successfully crossed the hardest part of learning programming, which is, getting started with your first program! -->
Hvis din utskrift er lik den over, gratulerer! - du har just kjørt ditt første Pythonprogram. Du har krysset den vanskligste barriæren ved å lære å programmere, som er, å komme i gang med det første programmet!

<!-- In case you got an error, please type the above program _exactly_ as shown above and run the program again. Note that Python is case-sensitive i.e. `print` is not the same as `Print` - note the lowercase `p` in the former and the uppercase `P` in the latter. Also, ensure there are no spaces or tabs before the first character in each line - we will see [why this is important](./basics.md#indentation) later. -->

Hvis du har fått en feil, vennligst skriv inn programmet _næyaktig_ slik som vist over og kjør programmet igjen. Merk at Python er varsom for store og små bokstaver (stor _A_ er ikke det samme som liten _a_. Dette heter case-sensitivity på engelsk.). `Print` er ikke det samme som `print`, legg merke til stor `P` første  og liten `p` andre gang. Og; sørg for at det ikke er noen mellomrom eller tabulator (tab) tegn før bokstavene i hver linje - vi skal se [hvorfor dette er så viktig](./basics.md#indentation) senere.

<!-- **How It Works** -->
**Hvordan det virker**

<!-- A Python program is composed of _statements_. In our first program, we have only one statement. In this statement, we call the `print` _statement_ to which we supply the text "hello world". -->
Et Pythonprogram består av _statments_. I vårt første program hadde vi bare et statment. I dette statmentet kaller vi `print` _statmentet_ som vi forer med teksten "hello world".

<!-- ## Getting Help -->
## Hvordan finne hjelp

<!-- If you need quick information about any function or statement in Python, then you can use the built-in `help` functionality. This is very useful especially when using the interpreter prompt. For example, run `help('len')` - this displays the help for the `len` function which is used to count number of items. -->
Hvis du trenger rask informasjon om noen funksjon eller statment i Python, da kan du bruke det innbygde `hjelp` funksjonalliteten. Dette er svært nyttig, særlig når du bruker det tolkende promptet. For eksempel, kjør `help('len')` - dette viser hjelp for bruk av `len`funksjonen som benyttes til å telle antall elementer.


<!-- TIP: Press `q` to exit the help. -->
TIPS: Trykk `q` for å avslutte hjelpen.

<!-- Similarly, you can obtain information about almost anything in Python. Use `help()` to learn more about using `help` itself! -->
På denne måten kan du skaffe informasjon om nesten alt mulig i Python. Bruk `help()` for å lære om hvorndan bruke `help`!

<!-- In case you need to get help for operators like `return`, then you need to put those inside quotes such as `help('return')` so that Python doesn't get confused on what we're trying to do. -->
Hvis du trenger hjelp om operasjoner som `return`, så skriver du bare inn dette inni anførselstegnene, slik: `help('return')`. På denne måten blir ikke Python forvirret av hva du prøver å finne hjelp om.

<!-- ## Summary -->
## Sammendrag

<!-- You should now be able to write, save and run Python programs at ease. -->
Du skal nå være i stand til å skrive, lagre og kjøre Pythonprogrammer med letthet.

<!-- Now that you are a Python user, let's learn some more Python concepts. -->
Nå som du er en Python-bruker, la oss lære mer Python.

---

<!-- [^1]: the author of the amazing 'Beginning Perl' book -->
[^1]: forfatteren av den fantastiske boken 'Beginning Perl'
