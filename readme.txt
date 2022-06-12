========================================================================
    ZADANIE IV
========================================================================
Napisz program ktory oblicza BER (Bit Error Rate) dla dwóch dowolnych plików.

Swoj¹ pracê utrzymaj na repozytorium na github. 

Twoja praca musi byæ udokumentowana przez kolejne commity.



Wymagania dla programu :



1. Program konsolowy. Jako dwa argumenty przyjmuje œcie¿ki do plików dla których oblicza wartoœæ BER.

2. Wynik obliczeñ drukowany jest w konsoli (Jako wynik podajemy: Iloœæ porównanych bitów, iloœæ ró¿nych bitów, wynik BER, czas obliczeñ)

3. Program tworzy plik log.txt w którym zapisuje swoje logi. Ka¿da wiadomoœæ rozpoczyna siê od timestamp'a.

4. Test 1: Przygotuj dwa identyczne pliki zawieraj¹ce binarnie zapisan¹ wartoœæ 0x55. Ka¿dy plik po 100 Bajtów. 

5. Test 2: Przygotuj dwa pliki ka¿dy po 100 bajtów. Pierwszy zawiera binarnie zapisan¹ wartoœæ 0x55. Drugi plik ró¿ni siê od pierwszego o dowolne 10 bitów.

6. Test 3: Przygotuje dwa pliki ka¿dy po 400 MB. Pierwszy zawiera binarnie zapisan¹ wartoœæ 0x55. Drugi plik zawiera binarnie zapisan¹ wartoœæ 0x50.


Podaj wynik dzia³ania programu BER dla podanych plików testowych (Wyniki zapisane w pliku z logami) 




========================================================================
    C++/WinRT task_iv_ber Project Overview
========================================================================

This project demonstrates how to get started consuming Windows Runtime 
classes directly from standard C++, using platform projection headers
generated from Windows SDK metadata files.

Steps to generate and consume SDK platform projection:
1. Build project initially to generate platform projection headers into
    your Generated Files folder.
2. Include a projection namespace header in your pch.h, such as 
    <winrt/Windows.Foundation.h>.
3. Consume winrt namespace and any Windows Runtime namespaces, such as 
    winrt::Windows::Foundation, from source code.
4. Initialize apartment via init_apartment() and consume winrt classes.

Steps to generate and consume a projection from third party metadata:
1. Add a WinMD reference by right-clicking the References project node
    and selecting "Add Reference...".  In the Add References dialog, 
    browse to the component WinMD you want to consume and add it.
2. Build the project once to generate projection headers for the 
    referenced WinMD file under the "Generated Files" subfolder.
3. As above, include projection headers in pch or source code 
    to consume projected Windows Runtime classes.

========================================================================
Learn more about C++/WinRT here:
http://aka.ms/cppwinrt/
========================================================================
