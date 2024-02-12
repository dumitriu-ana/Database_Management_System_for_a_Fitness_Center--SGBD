## Descrierea temei 
Proiectul reprezintă baza de bate a unei săli de sport. <br>
Există mai multe sedii ale sălii de sport, fiecare sediu având denumire, capacitate și data de deschidere proprie. Fiecare sediu se află la o adresă care conține oraș, stradă și număr.Fiecare sediu are unul sau mai mulți angajați. <br>
Pentru fiecare angajat știm numele, prenumele, telefonul, emailul, salariul, bonusul, sediul în care acesta lucrează, funcția acestuia și managerul care ii este superior. Fiecare angajat poate (daca acesta este antrenor) să susțină una sau mai multe ore de antrenament (ședințe) împreună cu un client. <br>
Fiecare ședință are un tip de antrenament (pentru fiecare tip de antrenament se cunosc denumirea care este alcatuită din inițiala sportului practicat și numărul ședinței respectivului client și nivelul, un numar de la 1 la 5, reprezentând dificultatea. <br>
Fiecare client participă la una sau mai multe sedinte. Despre fiecare client se cunosc urmatoarele: numele, prenumele, telefonul, data nasterii, emailul, data de începere și data de expirare a abonamentului și tipul de abonament. Fiecare client are un abonament (iar un abonament poate fi avut de unul sau mai mulți clienți). <br> 
Fiecare abonament are un tip de antrenament aferent (fiecare tip de antrenament face parte dintr-un abonament).  <br>

## Schema conceptuala
![image](https://github.com/dumitriu-ana/Database_Management_System_for_a_Fitness_Center--SGBD/assets/72306782/3c5b96fb-fb88-4f37-9061-e48beefffde9)

Să se creeze o noua tabelă numită ad_abonamente_premium, apoi să se includă în aceasta abonamentul cu id-ul 21 și să se afișeze tabela.
![image](https://github.com/dumitriu-ana/Database_Management_System_for_a_Fitness_Center--SGBD/assets/72306782/d4d8e7b5-82cc-43c9-9bec-7c01e6e59af7)

Să se șteargă sediile ale căror vechime depășește 3 ani sau a căror capacitate este mai mică de 25 de persoane. Dacă nu este posibil pentru că există angajați care lucrează în acest sediu, tratați excepția și afișați o eroare. 
![image](https://github.com/dumitriu-ana/Database_Management_System_for_a_Fitness_Center--SGBD/assets/72306782/b0d6a731-bb64-4303-bcc8-e83f2bf85baf)

Scrieți un program care crește bonusul angajatului cu numele Zegreanu cu două puncte procentuale. In cazul în care acesta nu există, tratati excepția și afisati un mesaj de eroare.
![image](https://github.com/dumitriu-ana/Database_Management_System_for_a_Fitness_Center--SGBD/assets/72306782/12cf691e-1406-4cc1-900c-7acdba4ad2ee)

Scrieți un program care afisează toți clientii care au abonamentul cu id-ul 21, folosind un cursor explicit.
![image](https://github.com/dumitriu-ana/Database_Management_System_for_a_Fitness_Center--SGBD/assets/72306782/97b70133-2500-4b68-b309-2a5afde72b14)

Scrieți un program care sa afișeze primii doi antrenori cu cele mai multe ședințe de antrenemant susținute, folosind un cursor explicit.
 ![image](https://github.com/dumitriu-ana/Database_Management_System_for_a_Fitness_Center--SGBD/assets/72306782/28c138d1-b945-40e7-a6df-e3cb1f94be6a)


Pentru angajații sediului nou, cu id-ul egal cu 10, să se calculeze care este remunerația (salariu și bonus) și care este prima pe care o vor obține în prima luna de lucru (remuneratie + 1.500), folosindu-se un cursor implicit. Datele referitoare la salariu se vor pastra intr-o nouă tabelă numită ad_salarii.
![image](https://github.com/dumitriu-ana/Database_Management_System_for_a_Fitness_Center--SGBD/assets/72306782/a76d3129-c053-4746-b6e3-749f7346da51)

Folosind un cursor implicit, să se afișeze pentru fiecare sediu care este id-ul, numarul de angajati și capacitatea acestuia.
![image](https://github.com/dumitriu-ana/Database_Management_System_for_a_Fitness_Center--SGBD/assets/72306782/d9caa265-357f-486f-b379-b91093d913eb)

Să se afișeze abonamentele și pentru fiecare abonament numele clientilor care dețin un astfel de abonament, utilizându-se doi cursori impliciti.
![image](https://github.com/dumitriu-ana/Database_Management_System_for_a_Fitness_Center--SGBD/assets/72306782/e44663e9-c472-4afa-a2a6-d45dd5442669)

Sa se creeze o procedură prin care sa se modifice bonusul primit de către un angajat al cărui id este primit ca parametru de intrare cu o valoare primită ca parametru. Să se afișeze noua valoare a bonusului și valoarea salariului înainte și după mdificare.
![image](https://github.com/dumitriu-ana/Database_Management_System_for_a_Fitness_Center--SGBD/assets/72306782/3f4ccfbb-bb03-4593-8d3b-c21da72f86af)

Să se scrie o funcție care returnează valoarea salariului net. Aceasta primește ca parametrii valoarea salariului brut și valoarea procentuala a impozitului.
![image](https://github.com/dumitriu-ana/Database_Management_System_for_a_Fitness_Center--SGBD/assets/72306782/acaf792a-014e-460e-95d8-52952979cc6c)

Să se scrie o funcție care primește ca parametru de intrare id-ul unei ședințe și returnează true (1) pentru acele sedințe care durează mai mult decât media duratelor tuturor ședințelor și false (0) altfel.
![image](https://github.com/dumitriu-ana/Database_Management_System_for_a_Fitness_Center--SGBD/assets/72306782/1d02130b-5e6b-4591-b40e-23d475955d93)

## Pachete

![image](https://github.com/dumitriu-ana/Database_Management_System_for_a_Fitness_Center--SGBD/assets/72306782/8de6360a-7857-49c4-a0c8-8bafac6b7d63)
![image](https://github.com/dumitriu-ana/Database_Management_System_for_a_Fitness_Center--SGBD/assets/72306782/d3d0a2de-7569-4fd8-ac05-30a422ccac37)


![image](https://github.com/dumitriu-ana/Database_Management_System_for_a_Fitness_Center--SGBD/assets/72306782/4fbf0d62-3e23-4957-a08b-a96ddffe244b)

![image](https://github.com/dumitriu-ana/Database_Management_System_for_a_Fitness_Center--SGBD/assets/72306782/ffef7600-ba4b-422c-9ac6-c1fdd0749c25)

## Trigger
Să se creeze un trigger care să nu permită valori mai mici de 30 de lei sau mai mari de 300 de lei pentru prețul unui abonament.
![image](https://github.com/dumitriu-ana/Database_Management_System_for_a_Fitness_Center--SGBD/assets/72306782/e4553cb3-1d8c-4a58-90c7-beaba189cd4a)

Să se creeze o tabelă în care să se rețină operația (insert, update, delete) pentru tabela ad_sedinte, cine a efectuat-o și data efectuarii care sunt asociate unui trigger care a fost declansat.
![image](https://github.com/dumitriu-ana/Database_Management_System_for_a_Fitness_Center--SGBD/assets/72306782/e44b080b-e83f-46aa-b475-6590afa11183)

Sa se creeze un trigger pentru tabela ad_sedii care să nu permită introducerea unei denumiri pentru sediu care sa aibă mai putin de 3 litere sau 3, să nu permită setarea unei capacități mai mari de 100 de oameni sau mai mici de 10 oameni și sa nu mermita setarea pentru data de deschidere mai veche de azi pentru un sediu.
![image](https://github.com/dumitriu-ana/Database_Management_System_for_a_Fitness_Center--SGBD/assets/72306782/4dc84cdf-c832-45a1-8e45-89ec450b28be)









