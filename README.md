# Implementacija OpenPGP i S/MIME protokola za zaštitu elektronske pošte

Ovaj repozitorijum sadrži kriptografsku i sistemsku implementaciju zaštite podataka na aplikativnom nivou.

## Sadržaj repozitorijuma
- `javni_kljuc.asc` - Eksportovani javni ključ generisan u okviru OpenPGP standarda korišćenjem alata GnuPG.
- `sifrovana_poruka.gpg` - Datoteka sa porukom šifrovanom upotrebom generisanog OpenPGP ključa.
- `smime_sertifikat.crt` - Samopotpisani X.509 digitalni sertifikat generisan kroz OpenSSL (2048-bit RSA).
- `smime_sifrovano.txt` - Datoteka šifrovana primenom S/MIME protokola i AES-256-CBC algoritma enkripcije.

Student Nemanja Simić (ns20230232@student.fon.bg.ac.rs)
