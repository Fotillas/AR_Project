# Μάθημα: Σχεδιασμός Περιβαλλόντων Διεπαφής

## Εγκατάσταση εργαλείων

### Για την συγγραφή του κώδικα:
Προτείνετε το [Brackets](https://brackets.io/) αλλά μπορείτε να χρησιμοποιήσετε όποιο άλλο θέλετε

### Για να εκτελείτε τον κώδικα τοπικά:
Ο κώδικας που θα χρησιμοποιήσουμε κάνει χρήση της κάμερας και επιπλέον πρέπει να δοκιμαστεί και σε κινητό τηλέφωνο. Γι αυτό τον λόγο πρέπει να εγκαταστηθεί ένας τοπικός (local)  HTTP server. Προτείνετε να χρησιμοποιηθεί το http server module της Python για τα Windows -υπάρχει ήδη στα MacOS & Linux. Αρχικά πρέπει να γίνει η εγκατάσταση:

1. Goto [Python.org](https://www.python.org/downloads/)
2. Στα Download Section κλικ Python “3xxx”
3. Επιλέξτε το <Windows Installer> για να κατεβάσετε το αρχείο εγκατάστασης
4. Εκτελέστε το
5. Επιλέξετε το “Add Python 3.xxx to PATH” κουτάκι επιλογής
6. Εγκαταστήστε και κλείστε το παράθυρο

1. Πηγαίντε στη γραμμή εντολών πληκτρολογώντας cmd
2. Με τις εντολές cd <όνομα καταλόγου>, cd.. και dir πηγαίνετε στον φάκελο που υπάρχει ο κώδικας και πληκτρολογείτε 
py -3 -m http.server για να ξεκινήσει να τρέχει ο local server στο default chanel 8000 ή εναλλακτικά πληκτρολογείστε το κανάλι που θέλετε
3. Ανοίξτε τον web browser και πληκτρολογείστε localhost:8000 και θα εμφανιστούν οι φάκελοι και τα αρχεία που μπορούν να εκτελεστούν τοπικά

### Αντιγραφή του αποθετηρίου και δημιουργία Github page 
Η εφαρμογή που θα χρησιμοποιήσετε υπάρχει online. Στη δημιουργία της, έχει χρησιμοποιηθεί η βιβλιοθήκη: MindAR και η js3. Δεν είναι όμως στόχος του μαθήματος να μάθετε προγραμματιστικά την επάυξηση, για αυτό τον λόγο ο κώδικας σας δίνεται έτοιμος! Πρέπει όμως να το “διαβάσετε” για να εμπλουτίσετε την εφαρμογή με βάση τους δικούς σας στόχους

Αν δεν έχετε ήδη λογαριασμό στο [Github](https://github.com/), μπορείτε να δημιουργήσετε έναν χρησιμοποιώντας το email του πανεπιστημίου. 
Στη συνέχεια συνδεθείτε στο αποθετήριο του μαθήματος και κάντε <fork> το αποθετήριο στον δικό σας λογαριασμό. 
Το αποθετήριο που μεταφέρατε στον λογαριασμό σας περιέχει έτοιμο τον κώδικα που μπορεί να επαυξήσει με ψηφιακό περιεχόμενο τον πραγματικό, χρησιμοποιώντας εικόνα - marker
Δημιουργία github σελίδας ώστε η εργασία σας να υπάρχει online στον λογαριασμό σας διαθέσιμη σε όποιον έχει το σύνδεσμο στη σελίδα. Ο κώδικας που αντιγράψατε δείχνει στο δικό μου αποθετήριο, οπότε πρέπει να γίνουν οι απαραίτητες τροποποιήσεις στην επιλογή settings / δημιουργία github page. Αναλυτικές οδηγίες υπάρχουν εδώ, από το βήμα 3 και μετά, και θα δοθούν και στο εργαστήριο. Περιμένετε λίγα λεπτά και το λινκ της σελίδας είναι έτοιμο. 
Ο κώδικας εκτελείται και μπορείτε ήδη να δείτε την επάυξηση, εάν χρησιμοποιήσετε τα προεπιλεγμένα 3 markers (xxx.png) που υπάρχει στον φάκελο targets, μέσα στον φάκελο assets. 

*Συγχαρητήρια*, έχετε έτοιμο τον βασικό κώδικα της εφαρμογής σας! Μένει ακόμα ένα βήμα για να ξεκινήσετε να εργάζεστε… Να κατεβάσετε τοπικά στον υπολογιστή σας το αποθετήριο που αποκτήσατε
Αποθηκεύουμε τοπικά το αποθετήριο στον υπολογιστή
Το αποθετήριο που αντιγράψατε πρέπει να αναγνωρίζεται σαν αποθετήριο και στον υπολογιστή σας και να υπάρχει επικοινωνία - ενημέρωση: 

Μπορείτε να χρησιμοποιήσετρε την εφαρμογή [git GUI](https://git-scm.com/download/win) που αφού την κατεβάσετε και την εγκαταστήσετε τοπικά στον υπολογιστή σας μπορείτε να κλωνοποιήσετε το αποθετήριο ώστε να εργάζεστε τοπικά και αφού ελέγχετε τις αλλαγές που θέλετε να κάνετε τότε να ενημερώνετε και το online. Αφού γίνει η κλωνοποίηση, μπορείτε να δουλέψετε τοπικά τον κώδικα στην εφαρμογή brackets ή Atom και να βλέπετε το αποτέλεσμα στον browser τοπικά.

### Συγχρονισμός και ενημέρωση του online αποθετηρίου.
Να σημειώσω πρώτα ότι όλη η δουλειά γίνεται τοπικά. Ενημέρωση του online αποθετηρίου γίνεται όταν είμαστε σίγουροι ότι δουλεύει αυτό που ετοιμάσαμε. Η διαδικασία, όπου και να γίνει, περιέχει τα ακόλουθα βήματα:
1. έχετε unstaged changes που πρέπει να γίνουν staged, τουλάχιστον αυτές που επιθυμείτε να ανεβάσετε - 
2. αφού ελέγξετε ότι έχουν επιλεγεί σωστά οι αλλαγές θα κάνετε commit. 
Να θυμάστε ότι κάθε commit πρέπει να συνοδεύεται με κάποιο αντιπροσωπευτικό σχόλιο - 
3. τέλος πρεπει να γίνει push στο github του commit
Αν γίνει οποιαδήποτε αλλαγή στο online αποθετήριο τότε για να μην υπάρξουν απώλειες - συγκρούσεις πρέπει να ενημερώνετε και το τοπικό αποθετήριο.

## Δημιουργία ψηφιακού περιεχομένου
### Δημιουργία της-ων εικόνας-ων - marker-s που ενεργοποιεί-ούν την επαύξηση:
Η εφαρμογή που έχετε δουλεύει ήδη με το  xxx.png αρχείο που βρίσκεται στον φάκελο targets, μέσα στον φάκελο assets. Μπορείτε να δοκιμάσετε την εφαρμογή, ενεργοποιώντας την επαύξηση με αυτό το αρχείο. 
Επίσης, προσέξτε ότι μέσα στον ίδιο φάκελο υπάρχει ένα αρχείο με το ίδιο όνομα xxx αλλά η επέκταση που έχει είναι .mind Αυτό συμβαίνει γιατί μια εικόνα πρέπει να υποστεί επεξεργασία ώστε να χρησμοποιηθεί σαν marker. 
Για να χρησιμοποιήσετε το δικό σας marker, αφού το δημιουργήσετε (ένα png αρχείο εικόνας), συνδεθείτε στο [image tracker compiler](https://hiukim.github.io/mind-ar-js-doc/tools/compile) και σύρετε το αρχείο -α στο ειδικό πλαίσιο και πατήστε <start>. 
Τοποθετείστε και τα δυο αρχεία μέσα στον φάκελο assets/targets ώστε η εφαρμογή να είναι εκτελέσιμη και μακριά από τον φυσικό χώρο… 
Για να δημιουργήσετε περισσότερα markers πρέπει να σύρετε ταυτόχρονα πολλά png files στο ειδικό πλαίσιο
Περισσότερες πληροφορίες μπορείτε να βρείτε [εδώ](https://hiukim.github.io/mind-ar-js-doc/quick-start/compile).

Για την εργασία πρέπει να δημιουργήσετε τουλάχιστον τρία (τρία) markers στο οποία θα συνδέσετε ψηφιακό περιεχόμενο

### Δημιουργία ψηφιακού περιεχομένου
Κάθε marker πρέπει να αντιστοιχεί σε ψηφιακό περιεχόμενο που θα έχει σκοπό να εμπλουτίσει την εμπειρία του χρήστη. Για τη δημιουργία του ψηφιακού περιεχομένου μπορεί να ανήκει στα παρακάτω είδη, ανάλογα με τις ανάγκες της εργασίας που έχετε επιλέξει:

(α) 3D Model (*.gltf) + Ήχος (*.mp3)

(β) Βίντεο (*.mp4)

  ### Πιθανές βελτιώσεις του κώδικα
  (α) Να φαίνεται το περιεχόμενο σεόλη την οθόνη του κινητού
  
  
  ## Τα παραδοτέα περιγράφονται στα issues του αποθετηρίου όπως και ο τρόπος συνεργασίας
