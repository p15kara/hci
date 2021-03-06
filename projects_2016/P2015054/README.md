#Τίτλος Εργασίας: Prime Snake
Μαρία-Νεφέλη Νικηφόρου
ΑΜ Π2015054
p15niki@ionio.gr

##Παραδοτέο 0

https://github.com/nefelinikiforou/pibookgr/tree/nefelinikiforou-patch-1/_quotes

##Παραδοτέο 1

Εκπαιδευτικό βιντεοπαιχνίδι με το εργαλείο Scratch

##Παραδοτέο 2

* Εργαλείο ανάπτυξης: Scratch

* Ηλικία: Το παιχνίδι είναι σχεδιασμένο για παιδιά (και των 2 φύλων) της Στ' τάξης του Δημοτικού και της Α' τάξης του Γυμνασίου (*).

* Θεματική διδακτική ενότητα: Μαθηματικά, Κεφάλαιο 13, Κριτήρια διαιρετότητας, Κεφάλαιο 14, Πρώτοι και σύνθετοι αριθμοί (Στ' 
  Δημοτικού):
  
  http://ebooks.edu.gr/modules/ebook/show.php/DSDIM101/301/2089,7414/
  http://ebooks.edu.gr/modules/ebook/show.php/DSDIM101/301/2089,7415/
  
  Μαθηματικά, Κεφάλαιο Α.1.5. Χαρακτήρες διαιρετότητας - ΜΚΔ - ΕΚΠ - Ανάλυση αριθμού σε γινόμενο πρώτων παραγόντων (Α'     
  Γυμνασίου):
 
  http://ebooks.edu.gr/modules/ebook/show.php/DSGYM-A200/293/2066,7183/
  
* Το παιχνίδι υλοποιεί το κόσκινο του Ερατοσθένη, για τους αριθμούς από το 2 έως το 100
  (Βλ. και https://el.wikipedia.org/wiki/Κόσκινο_του_Ερατοσθένη).
  
* Στόχος του παιχνιδιού είναι ο μαθητής να μάθει τα κριτήρια διαιρετότητας του 2, του 3 και του 5, αλλά και να ξεχωρίζει τους πρώτους από τους σύνθετους αριθμούς, μέχρι το 100.

(*) Η υλοποίηση του παιχνιδιού το καθιστά κατάλληλο και για παιδιά μικρότερων τάξεων ή/και για μαθητές που δεν έχουν διδαχτεί   ακόμα αυτή την ύλη, καθώς μαθαίνει τον παίχτη από την αρχή, δίχως να χρειάζεται προηγούμενη γνώση των πρώτων αριθμών ή των κριτηρίων διαιρετότητας.

* Δανεισμός κώδικα: https://scratch.mit.edu/projects/72303326/
* Η ιδέα βασίζεται στο κλασικό παιχνίδι Snake: (https://scratch.mit.edu/projects/72303326/)

**Snake**

![snake](https://cloud.githubusercontent.com/assets/22655733/20101783/1ddeed70-a5cc-11e6-9315-dd08da164d24.JPG)


**Σενάριο παιχνιδιού**

* Στην οθόνη εμφανίζονται φρούτα με τιμές από 1 έως 100, διατεταγμένα σε μορφή πίνακα 10x10, όπως στο κόσκινο του Ερατοσθένη.
  Το πρώτο Snake (Snake 2) εμφανίζεται και τρώει μόνο τα φρούτα των οποίων οι τιμές είναι πολλαπλάσια του 2. Αφού το Snake 2 
  φάει όλα τα πολλαπλάσια του 2, εξαφανίζεται. 

* Εμφανίζεται το Snake 3, που τρώει μόνο τα φρούτα με τιμές πολλαπλάσια του 3. Όταν φαγωθούν τα παραπάνω φρούτα, το Snake 3   εξαφανίζεται.

* Εμφανίζεται το Snake 5, που τρώει μόνο τα φρούτα με τιμές πολλαπλάσια του 5.  Όταν φαγωθούν τα παραπάνω φρούτα, το Snake 5  εξαφανίζεται.

* Εμφανίζεται, τέλος, το Snake 7, που τρώει μόνο τα φρούτα με τιμές πολλαπλάσια του 7.  Όταν φαγωθούν τα παραπάνω φρούτα, το 
  Snake 7 εξαφανίζεται.

* Στην οθόνη θα έχουν μείνει μόνο τα φρούτα με τιμές πρώτους αριθμούς και το παιχνίδι θα τελειώνει επιτυχώς.


**Οθόνη έναρξης**

![start](https://cloud.githubusercontent.com/assets/22655733/20102111/7f6b16f8-a5cd-11e6-82de-b38222ddfa68.JPG)
 
 Ο παίκτης πρέπει να πατήσει το εικονίδιο Play για να αρχίσει το παιχνίδι.

**Πρώτη εικόνα**

![1](https://cloud.githubusercontent.com/assets/22655733/20102158/b2dd9358-a5cd-11e6-85c2-7b90bc69812f.JPG)
Εμφανίζονται μήλα με τιμές 2-19 και το Snake 2 στο κέντρο της οθόνης.

**Δεύτερη εικόνα**

![2](https://cloud.githubusercontent.com/assets/22655733/20102196/e0f28b9a-a5cd-11e6-8951-e6ce12f8a057.JPG)

Το Snake 2 κινείται με τα βελάκια του πληκτρολογίου.

**Τρίτη εικόνα**

![3](https://cloud.githubusercontent.com/assets/22655733/20102217/f7ef2c2c-a5cd-11e6-92d2-5901669f1a2e.JPG)

Το Snake 2 αρχίζει να τρώει τα μήλα-πολ/σια του 2.

**Τέταρτη εικόνα**

![4](https://cloud.githubusercontent.com/assets/22655733/20102256/26b2adea-a5ce-11e6-9319-d58392154a48.JPG)

Το Snake 2 έχει φάει όλα τα πολ/σια του 2 και δεν μπορεί να φάει τα υπόλοιπα μήλα.

###Παράδειγμα (Demo online): https://scratch.mit.edu/projects/129676872/
Σημείωση: Προς το παρόν έχει υλοποιηθεί demo μόνο για τους αριθμούς από 2 έως 19 και μόνο με το Snake 2.

##Παραδοτέο 3

...

##Παραδοτέο 4

...

##Tελική Αναφορά

...
