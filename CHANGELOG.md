# Changelog

## v1.10.17 - 2026-11-04 20:29
- Versiunea 1.10.17: o singură autentificare pentru toate modulele unității.
- O autentificare Google pe unitate și calculator servește Transport Școlar, Burse și Contabilitate până la Deconectare; celelalte module nu mai cer logare (serviciul ISJ v44).
- Un modul al unității se folosește pe un singur calculator: deschis pe alt calculator, se închide aici, cu mesaj, iar celelalte module rămân autentificate; „Autentificare” îl preia înapoi fără Google.
- „Trimite” cere singur autentificarea, dacă lipsește, apoi trimite; Deconectarea închide toate modulele unității pe acest calculator.
- Executabil: release v1.10.17 (Situatii_ISJ_Buzau.exe, SHA-256 fd3f47c564c2defea2dfffc432ff150c3b8d6b96d9c23729f24cb3290d4598e5)
