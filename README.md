# Smart Chargers Application

Για το τρέξιμο της ιστοσελίδας:

Έχοντας κατεβάσει το zip και κάνει extract τα περιεχόμενά του, θέλετε να ανοίξετε τον φάκελο που βρισκόταν στο εσωτερικό του zip στο πρόγραμμα VS Code, μόλις το έχετε κάνει αυτό, προχωρήστε παρακάτω.
Για το τρέξιμο των παρακάτω εντολών για το άνοιγμα της ιστοσελίδας είναι απαραίτητη η εγκατάσταση του περιβάλλοντος εκτέλεσης Node.js, αντίστοιχα για τον προσομοιωτή είναι απαραίτητο να έχετε εγκατεστημένη μία πρόσφατη έκδοσης της Python.
Για το άνοιγμα της ιστοσελίδας τώρα, κατεβάστε πρώτα τα αναγκαία πακέτα node με `npm install`(προσοχή ο φάκελος όπου θα τρέχει το terminal να είναι ο Omada09_Smart_Chargers, δηλαδή ο άμεσος parent folder των περιεχομένων). Έπειτα γράψτε την εντολή `npm run watch` στο terminal, η ιστοσελίδα θα βρίσκεται στο σύνδεσμο που θα εμφανιστεί στο terminal.

Παράλληλα μπορείτε να τρέξετε και τον προσομοιωτή του συστήματος φορτιστή-μπάρας ασφάλισης απλώς τρέχοντας το αρχείο nfc_reader.py.

Σε συνδυασμό αυτά τα δύο προγράμματα μπορούν να χρησιμοποιηθούν για να προσομοιωθεί το σύστημα κρατήσεων σε ένα δίκτυο έξυπνων φορτιστών αυτοκινήτων. 
Ένας χρήστης μπορεί να αυθεντικοποιηθεί μέσω του συστήματος είτε με τη χρήση της ιστοσελίδας είτε σκανάροντας την κάρτα του σε έναν nfc αισθητήρα συνδεδεμένο στο σύστημα. 
Άμα έχει κάνει κράτηση εκείνη την ώρα στον αναφερόμενο φορτιστή τότε το σύστημα θα ελέγξει την εγκυρότητα των στοιχείων του και θα τον αυθεντικοποιήσει, θα ανέβει η μπάρα και θα μπορέσει να μπει στη θέση φόρτισης και να φορτίσει το όχημά του.

Για να τερματίσετε τη λειτουργία της ιστοσελίδας απλά επιλέξτε το terminal στο οποίο σας εμφάνισε το σύνδεσμό της και πατήστε(στο πληκτρολόγιο): (Control)+(c), έπειτα (y) και τέλος (Enter).
Ο προσομοιωτής τερματίζει αυτόματα, κλέινοντας το παράθυρο στο οποίο εμφανίζεται.

(Σημείωση: όλα τα passwords στους διάφορους λογαριασμούς έχουν γίνει hashed, είναι όλοι όμως ίδιοι: test123)
