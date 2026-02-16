Digitalizacija i Spektrogramska Analiza Govornog Signala

Opis projekta:

Ovaj projekat predstavlja praktičnu implementaciju procesa digitalne obrade govora, sa fokusom na spektrogramsku analizu i frekvencijsku interpretaciju govornog signala korištenjem MATLAB okruženja.

Cilj projekta je demonstrirati kompletan tok obrade govora — od snimanja analognog signala, preko A/D konverzije i frekvencijske analize, do filtriranja i simulacije D/A rekonstrukcije.

Projekt obuhvata sljedeće ključne koncepte iz oblasti digitalne obrade signala:

Analogno-digitalna konverzija (A/D)

Uzorkovanje i kvantizacija

Nyquistov teorem

Diskretna Fourierova transformacija (DFT)

Brza Fourierova transformacija (FFT)

Kratkovremenska Fourierova transformacija (STFT)

Spektrogramska analiza

Formanti (F1, F2, F3)

Digitalno filtriranje (Butterworth niskopropusni filtar)

Simulacija D/A konverzije interpolacijom

Praktična implementacija - Snimanje govora

Analizirana je ista rečenica izgovorena u različitim modalitetima:

Normalan ton

Šapat

Povišen ton

Kombinacija šapata i povišenog tona

Brzi i spori tempo govora

Signal je snimljen mobilnim uređajem (44.1 kHz, 16-bit), a zatim konvertovan u WAV format radi obrade u MATLAB-u.

Izvršene analize

Vremenski prikaz signala

Spektrogramska analiza (STFT)

Identifikacija formantskih područja

Filtriranje pomoću Butterworth filtra 6. reda (fc = 3500 Hz)

Filtriranje bez faznog pomaka korištenjem filtfilt()

Poređenje govora prije i poslije filtriranja

Simulacija rekonstrukcije signala linearnom interpolacijom

Tehnički detalji

Prozor: Hamming (512 uzoraka)

Preklapanje: 50%

FFT veličina: 1024

Frekvencija uzorkovanja: 44.1 kHz

Bitna dubina: 16-bit

🎯 Cilj projekta

Demonstrirati kako se analogni govorni signal može:

Digitalizovati

Analizirati u frekvencijskom domenu

Filtrirati radi uklanjanja visokofrekventnog šuma

Rekonstruisati u približan analogni oblik
