# Changelog

## v1.10.16 - 2026-11-04 12:11
- Versiunea 1.10.16: autentificarea păstrată pe fiecare unitate și trimiterea Contabilitate mai rapidă.
- Autentificarea în Contabilitate se păstrează pe calculator pentru fiecare unitate, separat de Transport și de celelalte unități, până la Deconectare; o logare închide doar sesiunea aceleiași unități de pe alt calculator (serviciul ISJ v43).
- Trimiterea unei situații Contabilitate se face în două cereri la serviciul ISJ în loc de patru: încărcările fișierelor se deschid la începerea trimiterii și se confirmă la finalizare.
- Executabil: release v1.10.16 (Situatii_ISJ_Buzau.exe, SHA-256 67f08e9918381060712aa320d056370930e6103660dab5b5b0763a1b2cff089a)
