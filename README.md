# 📄 System Documentation

**Last updated: 04. April 2025**

---

## 📚 Table of Contents
- [🧠 Skill Search](#-skill-search)
- [🧠 Skill Search – Results View](#-skill-search--results-view)
- [🧠 Skill Search – No Direct Results View](#-skill-search--no-direct-results-view)
- [🧱 Buckets View](#-buckets-view)
- [🧱 Bucket Detail View](#-bucket-detail-view)
- [➕ Add Bucket View](#-add-bucket-view)
- [✏️ Edit Bucket Level View](#-edit-bucket-level-view)
- [➕ Add Skill / Expectation / Tool / Knowledge Modal](#-add-skill--expectation--tool--knowledge-modal)
- [➕ Add New Level to Bucket](#-add-new-level-to-bucket)
- [👥 Team Overview View](#-team-overview-view)
- [📊 Admin Dashboard](#-admin-dashboard)
- [👥 Team Overview](#-team-overview)
- [✏️ Edit Team](#-edit-team)
- [❌ Delete Team](#-delete-team)
- [👥 Manage Team Members](#-manage-team-members)
- [🧠 Skill Search](#-skill-search)
- [🛡️ Evaluation](#-evaluation)
- [👥 People Overview](#-people-overview)
- [➕ Add New Member](#-add-new-member)
- [📋 Sažetak Izvještaja](#-pregled-sažetka-izvještaja)


---

# 🧠 Skill Search

## Opis
Stranica omogućava superadminu i Hani-ju da pretražuju sve zaposlenike po vještinama. Rezultati pretrage prikazani su kao kartice sa osnovnim informacijama o zaposleniku.

## Ključne funkcionalnosti
- Skill Search input za pretragu vještina
- Brojač pronađenih korisnika ("Found 100")
- Lista zaposlenika prikazana kroz kartice
- Kartica prikazuje ime, glavnu i sekundarnu rolu, trenutni cilj i dugme za detaljan pregled ("See Full")
- Sidebar za navigaciju kroz glavne sekcije (Skill Search, Buckets, Evaluation, People)

## Ko koristi
Superadmin i CTO (Hani) za brzo pronalaženje zaposlenih na osnovu vještina i planiranje resursa.

## Interakcija
Unos ključne riječi u polje za pretragu filtrira prikazane zaposlenike. Klik na "See Full" otvara detaljan profil zaposlenika. Klik na navigaciju u sidebaru vodi na druge sekcije dashboarda.

---

![🧠 Skill Search](images/skill_search.png)

---

# 🧠 Skill Search – Results View

## Opis
Stranica prikazuje rezultate pretrage nakon što admin ili CTO pretraže određenu vještinu. Prikazuje direktne poklapanja i AI-predložene potencijalno dobre kandidate.

## Ključne funkcionalnosti
- Search bar sa prikazom unesenog termina (npr. "Business Analyst")
- Prikaz broja direktnih pogodaka ("Found 3")
- Kartice zaposlenika sa imenom, trenutnom i sekundarnom rolom, trenutnim ciljem i dugmetom "See Full"
- Sekcija za prikaz potencijalno dobrih kandidata ("Found 1 Potential good candidates")

## Ko koristi
Superadmin i CTO (Hani) za traženje zaposlenih koji odgovaraju projektu ili otvorenoj poziciji.

## Interakcija
Unos termina u search bar i prikaz rezultata. Klik na "See Full" otvara detaljan profil korisnika. Pregled i poređenje direktnih i AI-predloženih kandidata.

---

![🧠 Skill Search – Results View](images/skill_search_result.png)

---

# 🧠 Skill Search – No Direct Results View

## Opis
Stranica prikazuje situaciju kada nema direktnih poklapanja za unesenu vještinu, ali se prikazuje AI-predložen kandidat koji ima srodne kompetencije.

## Ključne funkcionalnosti
- Search bar sa prikazom pretraženog termina (npr. "Business Analyst")
- Obavijest "Found 1 Potential good candidates"
- Kartica AI-predloženog zaposlenika sa imenom, rolom, sekundarnom rolom i trenutnim ciljem
- Dugme "See Full" za otvaranje detaljnog profila

## Ko koristi
Superadmin i CTO (Hani) kada žele otkriti kandidate sa potencijalom za rolu, čak i ako ne postoji direktan match.

## Interakcija
Unos termina u search bar → prikaz potencijalnih kandidata. Klik na "See Full" za pregled detaljnog profila.

---

![🧠 Skill Search – No Direct Results View](images/skill_search_no_result.png)

---

# 🧱 Buckets View

## Opis
Stranica omogućava superadminu i CTO-u da pregledaju, pretražuju i uređuju sve postojeće bucket-e (uloge) unutar firme.

## Ključne funkcionalnosti
- Search bar za pretragu bucket-a po imenu
- Dugme "Add Bucket" za kreiranje nove uloge
- Kartice za svaki bucket sa imenom, opisom, nivoima i dugmetom "Edit Bucket"
- Sidebar za navigaciju između sekcija

## Ko koristi
Superadmin i CTO (Hani) za strukturiranje karijernih puteva i upravljanje pozicijama unutar firme.

## Interakcija
Unos termina u "Bucket Search" filtrira bucket-e. Klik na "Add Bucket" otvara formu za kreiranje nove uloge. Klik na "Edit Bucket" vodi na uređivanje bucket-a.

---

![🧱 Buckets View](images/buckets_view.png)

---

# 🧱 Bucket Detail View

## Opis
Detaljni pregled pojedinačnog bucket-a (uloge), gdje su prikazani svi nivo-i i njihove specifične informacije.

## Ključne funkcionalnosti
- Pregled svih nivoa
- "Add Level +" dugme za kreiranje novog nivoa
- Detalji selektovanog nivoa (Expectations, Skills, Tools, Knowledge, To Advance)
- Dugme "Edit Level" za uređivanje informacija

## Ko koristi
CTO (Hani) i Superadmin za definisanje karijernih puteva.

## Interakcija
Klik na nivo u hijerarhiji prikazuje njegove detalje. Klik na "Edit Level" omogućava uređivanje.

---

![🧱 Bucket Detail View](images/bucket_detail_view.png)

---

# ➕ Add Bucket View

## Opis
Stranica za kreiranje novog bucket-a (uloge) u firmi.

## Ključne funkcionalnosti
- Unos naslova novog bucket-a
- Dugme "Add Level +" za dodavanje nivoa
- Dugme "Save Bucket" za potvrdu kreiranja

## Ko koristi
Superadmin i CTO (Hani) za kreiranje novih karijernih puteva.

## Interakcija
Unos naslova bucket-a i kreiranje nivoa. Klik na "Save Bucket" za potvrdu.

---

![➕ Add Bucket View](images/bucket_add_view.png)

---

# ✏️ Edit Bucket Level View

## Opis
Stranica omogućava uređivanje postojećeg nivoa unutar bucket-a.

## Ključne funkcionalnosti
- Editable polje za naziv nivoa
- Sekcije za Expectations, Skills, Tools, Knowledge, To Advance
- "Edit Level" dugme za spremanje izmjena
- "Save Bucket" dugme za globalno spremanje

## Ko koristi
CTO (Hani) i Superadmin za održavanje karijernih puteva.

## Interakcija
Direktno uređivanje i spremanje sekcija.

---

![✏️ Edit Bucket Level View](images/bucket_edit_level_view.png)

---

# ➕ Add Skill / Expectation / Tool / Knowledge Modal

## Opis
Popup modal za dodavanje novih skillova, očekivanja, alata ili znanja u nivo.

## Ključne funkcionalnosti
- Polje za unos naziva
- Dugme "Save Skill" za potvrdu unosa

## Ko koristi
Superadmin i CTO (Hani) dok uređuju nivoe.

## Interakcija
Unos i spremanje novog elementa u odgovarajući odjeljak.

---

![➕ Add Skill / Expectation / Tool / Knowledge Modal](images/bucket_add_skill_modal.png)

---

# ➕ Add New Level to Bucket

## Opis
Prikazuje inicijalno stanje novog nivoa nakon dodavanja u bucket.

## Ključne funkcionalnosti
- Unos naziva novog nivoa
- Prazna polja za sekcije
- Spremanje izmjena

## Ko koristi
Superadmin i CTO (Hani) za proširivanje karijernih puteva.

## Interakcija
Unos informacija i spremanje novog nivoa.

---

![➕ Add New Level to Bucket](images/bucket_add_level_view.png)

---

# 👥 Team Overview View

## Opis
Stranica prikazuje pregled svih formiranih timova u firmi.

## Ključne funkcionalnosti
- Search bar za pretragu timova
- Grid kartice za svaki tim (naziv, team lead)
- Dugmad "View" i "Edit"

## Ko koristi
Superadmin i CTO (Hani) za organizaciju timova.

## Interakcija
Pretraga timova, pregled članova, uređivanje tima.

---

![👥 Team Overview View](images/team_overview_view.png)

---

# 📊 Admin Dashboard

## Opis
Stranica prikazuje pregled statusa promocija, performansi timova i analitike vještina unutar firme.

## Ključne funkcionalnosti
- Pregled pending promocija
- Prikaz promocija po kvartalima
- Tabela najboljih timova (Leaderboard)
- Analiza vještina koje zahtijevaju najviše vremena za razvoj

## Ko koristi
Superadmin i CTO (Hani) za strateško praćenje razvoja i planiranje intervencija.

## Interakcija
Pregled sažetih podataka, klik na promocije za više detalja, navigacija ka detaljima timova i zaposlenih.

---

![📊 Admin Dashboard](images/superadmin_hani_dashboard.jpg)

---

# 👥 Team Overview

## Opis
Stranica prikazuje detaljan pregled odabranog tima, uključujući članove, informacije o timu i povezane projekte.

## Ključne funkcionalnosti
- Lista članova tima
- Informacije o nazivu, opisu i tehnologijama tima
- Veza sa aktivnim projektima
- Opcije za uređivanje i brisanje tima

## Ko koristi
Team Lead i Superadmin za organizaciju i analizu timova.

## Interakcija
Klik na članove za upravljanje, edit dugme za izmjenu podataka tima, delete dugme za brisanje tima.

---

![👥 Team Overview](images/pregled_odabranog_tima_novi_izgled.jpg)

---

# ✏️ Edit Team

## Opis
Stranica za uređivanje podataka odabranog tima, uključujući naziv, tehnologije i projekat na kojem tim radi.

## Ključne funkcionalnosti
- Editabilna polja za naziv i opis tima
- Dodavanje/brisanje tehnologija
- Povezivanje sa projektom
- Spremanje izmjena

## Ko koristi
Team Lead i Superadmin za održavanje ažurnih informacija o timovima.

## Interakcija
Unos novih vrijednosti u polja, dodavanje tehnologija kroz dropdown, spremanje promjena klikom na dugme "Save".

---

![✏️ Edit Team](images/uredivanje_odabranog_tima.jpg)

---

# ❌ Delete Team

## Opis
Modal za potvrdu brisanja tima sa svim njegovim članovima i povezanim podacima.

## Ključne funkcionalnosti
- Prikaz upozorenja o trajnom brisanju
- Dugme za potvrdu brisanja
- Dugme za otkazivanje akcije

## Ko koristi
Team Lead i Superadmin u slučaju gašenja ili reorganizacije tima.

## Interakcija
Klik na "Delete" dugme trajno briše tim; klik na "Cancel" zatvara modal bez akcije.

---

![❌ Delete Team](images/brisanje_tima.jpg)

---

# 👥 Manage Team Members

## Opis
Stranica za upravljanje članovima tima — dodavanje novih, uklanjanje postojećih i ažuriranje njihovih uloga.

## Ključne funkcionalnosti
- Prikaz svih trenutnih članova tima
- Dodavanje novih članova
- Brisanje članova iz tima
- Uređivanje uloga članova

## Ko koristi
Team Lead i Superadmin za održavanje pravilne strukture tima.

## Interakcija
Klik na dugme "Add Member" za dodavanje, dugme za brisanje člana pored imena, inline edit za uloge.

---

![👥 Manage Team Members](images/upravljanje_clanova_tima.jpg)

---

# 🧠 Skill Search
## Opis
Stranica omogućava superadminu i CTO-u brzo pretraživanje svih zaposlenika po vještinama.

## Ključne funkcionalnosti
- Pretraga zaposlenika po vještinama
- Prikaz kartica zaposlenika sa opcijama za uređivanje i promociju
- Navigacija kroz sekcije dashboarda

## Ko koristi
Superadmin i CTO.

## Interakcija
Unos ključne riječi filtrira zaposlenike, klik na "Edit" ili "Promote" otvara dodatne opcije.

![🧠 Skill Search](images/skill_search.png)

---

# 🛡️ Evaluation
## Opis
Stranica za pregled zaposlenika spremnih za promociju i upravljanje izvještajima.

## Ključne funkcionalnosti
- Lista zaposlenika spremnih za promociju
- Pisanje komentara i izvještaja
- Pregled svih izvještaja

## Ko koristi
Superadmin i CTO.

## Interakcija
Klik na "See Reports" otvara detaljan pregled korisničkih izvještaja.

![🛡️ Evaluation](images/evaluation.png)

---

# 👥 People Overview
## Opis
Stranica za administraciju zaposlenika, omogućava pretragu, uređivanje i dodavanje zaposlenih.

## Ključne funkcionalnosti
- Prikaz svih zaposlenika
- Brza pretraga i uređivanje profila
- Dodavanje novih zaposlenika

## Ko koristi
Superadmin.

## Interakcija
Klikom na "Edit" otvara se detaljan prikaz i uređivanje zaposlenika.

![👥 People Overview](images/people_overview.png)

---

# ➕ Add New Member
## Opis
Ekran za dodavanje novih članova u tim, sa odabirom pozicije.

## Ključne funkcionalnosti
- Pretraga kandidata po ključnim riječima
- Odabir pozicije prije dodavanja
- Pregled članova prije potvrde

## Ko koristi
Superadmin i CTO.

## Interakcija
Dodavanje kandidata klikom na "Add to Team", potvrda klikom na "Done".

![➕ Add New Member](images/add_member.png)

---

# 📋 Pregled sažetka izvještaja
## Opis
Stranica prikazuje skraćeni sažetak izvještaja zaposlenika.

## Ključne funkcionalnosti
- Vizualni pregled ciljeva
- Sažetak izvještaja

## Ko koristi
Superadmin i CTO.

## Interakcija
Klik na "See Summary" otvara pregled izvještaja.

![📋 Pregled sažetka izvještaja](images/see_summary.png)
