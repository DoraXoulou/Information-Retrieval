# Information-Retrieval
Creation of a search engine in Java 

Μηχανή Αναζήτησης Πληροφορίας από Επιστημονικά Άρθρα

ΠΕΡΙΓΡΑΦΗ: Αυτή η μηχανή αναζήτησης είναι σχεδιασμένη για την αποδοτική αναζήτηση και παρουσίαση επιστημονικών άρθρων. Χρησιμοποιεί τη βιβλιοθήκη Lucene για να δημιουργήσει ένα ευρετήριο που επιτρέπει την εύκολη ανάκτηση άρθρων βάσει της συνάφειάς τους με το ερώτημα του χρήστη. Τα έγγραφα που ανακτώνται είναι επιστημονικά άρθρα από τη συλλογή NIPS Papers 1987-2017.

ΤΡΟΠΟΣ ΥΛΟΠΟΙΗΣΗΣ: Υλοποιείται σε Eclipse και προαπαιτείται να εγκαταστήσουμε τις βιβλιοθήκες της Lucene.

ΤΡΟΠΟΙ ΑΝΑΖΗΤΗΣΗΣ: Απλή Αναζήτηση: Αναζήτηση με λέξεις-κλειδιά που μπορεί να βρίσκονται στον τίτλο, στην περίληψη ή στο πλήρες κείμενο του άρθρου. Αναζήτηση Βάσει Πεδίου: Αναζήτηση σε συγκεκριμένα πεδία όπως ο τίτλος ή η χρονιά δημοσίευσης. Αναζήτηση σε Χρονικό Εύρος: Αναζήτηση άρθρων που δημοσιεύτηκαν σε συγκεκριμένο χρονικό διάστημα. Ιστορικό Αναζητήσεων: Δυνατότητα προβολής και διαχείρισης του ιστορικού των αναζητήσεων.

ΟΔΗΓΙΕΣ ΧΡΗΣΗΣ: Απλή Αναζήτηση: Εισάγετε μια λέξη-κλειδί στο πεδίο "Query" και πατήστε "Search".

Αναζήτηση Βάσει Πεδίου: Πατήστε "Field Search", εισάγετε το πεδίο στο οποίο θέλετε να αναζητήσετε (π.χ. "title") και την αντίστοιχη λέξη-κλειδί στο πεδίο "Query".

Αναζήτηση σε Χρονικό Εύρος: Πατήστε "Range Search", εισάγετε το πεδίο "year" και το εύρος των χρονολογιών στα πεδία "Lower Term" και "Upper Term".

Ιστορικό Αναζητήσεων: Πατήστε "History" για να δείτε τις προηγούμενες αναζητήσεις σας. Πατήστε "Refresh" για να ανανεώσετε τη λίστα.

Αναδιάταξη με βάση τη χρονολογία: Πατήστε "Sort by Year" για να αναδιαταχθούν τα αποτελέσματα με βάση τη χρονολογία δημοσίευσης τους.

ΤΕΧΝΙΚΕΣ ΛΕΠΤΟΜΕΡΕΙΕΣ:

Ευρετηριοποίηση: Χρησιμοποιούνται διάφορα φίλτρα για την προεπεξεργασία του κειμένου, όπως η αφαίρεση stop words, stemming, και συνωνυμίες. Τα δεδομένα αποθηκεύονται σε κανονικοποιημένη μορφή για την καλύτερη ανάκτηση πληροφοριών.

Αναζήτηση: Η αναζήτηση εκτελείται μέσω του QueryParser και τα αποτελέσματα επιστρέφονται με σειρά συνάφειας. Υποστηρίζονται διαφορετικοί τύποι αναζητήσεων (απλή, βάσει πεδίου, χρονικό εύρος).

Παρουσίαση Αποτελεσμάτων: Τα αποτελέσματα εμφανίζονται σε μια λίστα, με τις λέξεις-κλειδιά να επισημαίνονται με έντονα γράμματα. Υπάρχει δυνατότητα ταξινόμησης των αποτελεσμάτων ανά έτος.
