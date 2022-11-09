# ISSEL-Announcements

![logo](https://github.com/robotics-4-all/Announcements/blob/master/Capture.PNG?raw=true)

# Διαθέσιμες διπλωματικές ISSEL περιόδου Απριλίου 2022

Παρακάτω μπορείτε να βρείτε τα νέα θέματα διπλωματικών της Ομάδας Ευφυών Συστημάτων και Τεχνολογίας Λογισμικού. Οι φοιτητές που ενδιαφέρονται για διπλωματική εργασία παρακαλούνται να συμπληρώσουν [τη φόρμα έκφρασης ενδιαφέροντος](https://issel.ee.auth.gr/diathesimes-diplwmatikes/%cf%86%cf%8c%cf%81%ce%bc%ce%b1-%ce%ad%ce%ba%cf%86%cf%81%ce%b1%cf%83%ce%b7%cf%82-%ce%b5%ce%bd%ce%b4%ce%b9%ce%b1%cf%86%ce%ad%cf%81%ce%bf%ce%bd%cf%84%ce%bf%cf%82/) έως και τις <>. Μπορείτε να βρείτε ένα αρχείο με παρουσίαση των διπλωματικών στον σύνδεσμο: [to be announced](XXX).
Τέλος, βρείτε σχετικές ερωτήσεις σχετικά με τη διαδικασία επιλογής και τις απαιτήσεις στον παρακάτω σύνδεσμο: [Link](https://issel.ee.auth.gr/sixnes-erwtiseis/).

Περιεχόμενα:
- [TH-1/ Χρήση imitation learning και reinforcement learning για την εκμάθηση οδηγικής συμπεριφοράς αυτόνομου αυτοκινήτου](#th-1)
- [TH-2/ Δημιουργία συστήματος υπενθύμισης αναγκαίων αντικειμένων σε άτομα με νοητική εξασθένηση κατά την έξοδό τους από το σπίτι](#th-2)
- [TH-3/ Ανάπτυξη συστήματος παραγωγής ερωταπαντήσεων από κείμενα (Question Generation system)](#th-3)
- [TH-4/ Ανάπτυξη ψηφιακού βοηθού ερωταπαντήσεων για ιστοσελίδες](#th-4)
- [TH-5/ Ανάλυση Εργασιών Λογισμικού και Σχετικού Κώδικα από Δεδομένα Συστημάτων Ελέγχου Εκδόσεων](#th-5)

---
## TH-1
**Χρήση imitation learning και reinforcement learning για την εκμάθηση οδηγικής συμπεριφοράς αυτόνομου αυτοκινήτου**

Ως γνωστόν, η τεχνολογία των αυτόνομων αυτοκινήτων είναι μία από τις πιο αναπτυσσόμενες ερευνητικές τάσεις, τόσο σε πανεπιστήμια, όσο και σε αυτοκινητοβιομηχανίες. Σχεδόν όλες οι μεγάλες εταιρίες κατασκευής αυτοκινήτων πλέον διαθέτουν τμήμα έρευνας σχετικό με autonomous cars, στοχεύοντας σε ένα μερίδιο της μελλοντικής αγοράς. Στην παρούσα διπλωματική εργασία στόχος είναι να γίνει ανάπτυξη συμπεριφορών χαμηλού επιπέδου (lane keeping, intersection handling, stop sign κτλ) με χρήση imitation learning και reinforcement learning, δηλαδή αρχικά εκμάθησης μέσω παρατήρησης ορθών συμπεριφορών, και συνέχεια της εκμάθησης με χρήση ανταμοιβών (rewards). Τα δεδομένα εισόδου θα είναι το lidar του αμαξιού, όπως και οι actors που υπάρχουν στον κόσμο, μέσω του Carla API.

- **Επιθυμητές γνώσεις**: Καλή γνώση προγραμματισμού σε Python, ιδανικά γνώση Reinforcement Learning 
- **Εμπλεκόμενες Τεχνολογίες – Γνώσεις που θα αποκτηθούν**: Carla simulator, Autonomous driving, Python, Reinforcement Learning
- **Εκτιμώμενος Χρόνος Περάτωσης**: 9 Μήνες
- **Συνεργαζόμενος Ερευνητής**: Τσαρδούλιας Εμμανουήλ
- **Σχετικό link**: https://carla.org/
---
## TH-2
**Δημιουργία συστήματος υπενθύμισης αναγκαίων αντικειμένων σε άτομα με νοητική εξασθένηση κατά την έξοδό τους από το σπίτι**

Ένα από τα προβλήματα που αντιμετωπίζουν τα άτομα με νοητική εξασθένηση (κυρίως τα άτομα που πάσχουν από πρώιμη άνοια) είναι η έξοδος από την οικία τους χωρίς κάποια αντικείμενα που είναι απαραίτητο να διαθέτουν, όπως για παράδειγμα τα κλειδιά τους ή το κινητό τους τηλέφωνο. Αντίστοιχο πρόβλημα είναι το misplacement των αντικειμένων, αφού η θέση που τοποθετήθηκαν μπορεί να ξεχαστεί. Στην παρούσα διπλωματική σκοπός είναι να κατασκευαστεί ένα σύστημα υπενθύμισης ή εντοπισμού αντικειμένων τα οποία έχουν γίνει tag με κάποια τεχνική RF. Το σύστημα θα απαρτίζεται από ένα hat για μία generic φορητή συσκευή ΙοΤ που έχει παράξει το εργαστήριο, η οποία θα τοποθετηθεί δίπλα από την πόρτα του σπιτιού και θα σκανάρει για τα tagged αντικείμενα. Επίσης, το συστημα θα διαθέτει μία ακόμη απλούστερη συσκευή η οποία θα εντοπίζει το άνοιγμα και το κλείσιμο της πόρτας. Ο συνδυασμός των δύο αυτών συσκευών θα μπορεί να κατανοήσει το πότε άνοιξε/έκλεισε η πόρτα και το εάν τα επιθυμητά αντικείμενα ήταν στην εμβέλεια του συστήματος την χρονική αυτή περίοδο. Εάν δεν ήταν, το σύστημα πρέπει να παράξει μία ηχητική ειδοποίηση.

- **Επιθυμητές γνώσεις**: Ηλεκτρονική, επιθυμητή η γνώση κατασκευής πλακετών (KiCad ή κάποιο παρεμφερές λογισμικό), C, Python
- **Εμπλεκόμενες Τεχνολογίες – Γνώσεις που θα αποκτηθούν**: Σχεδίαση & υλοποίηση πλακετών, ενσωμάτωση αισθητήρων
- **Εκτιμώμενος Χρόνος Περάτωσης**: 9 Μήνες
- **Συνεργαζόμενος Ερευνητής**: Ευριπίδης Χονδροματίδης, Support: Μάνος Τσαρδούλιας
---
## TH-3
**Ανάπτυξη συστήματος παραγωγής ερωταπαντήσεων από κείμενα (Question Generation system)**

Το state of the art στην κατανόηση κειμένου για την απάντηση ερωτήσεων (Question Answering task) περιλαμβάνει την εκπαίδευση Machine Learning μοντέλων να βρίσκουν την απάντηση χρησιμοποιώντας ως πληροφορία κάθε φορά την ερώτηση και ένα πλαίσιο γνώσης (context). Ωστόσο, λίγη σημασία έχει δοθεί στην ανάπτυξη μοντέλων που μπορούν να δημιουργήσουν ερωτήσεις χρησιμοποιώντας αντίστοιχα μόνο ένα κείμενο ως πληροφορία, το λεγόμενο Question Generation task, καθώς αυτό απαιτεί μια υψηλότερου επιπέδου κατανόηση του κειμένου, αλλά και της γλώσσας συνολικά. Στόχος αυτής της διπλωματικής είναι η μελέτη αυτού του task και η ανάπτυξη διάφορων μοντέλων και τεχνικών, χρησιμοποιώντας state of the art γλωσσικά μοντέλα (Language Models). Τέλος, θα παρουσιαστεί η λειτουργικότητα του συστήματος αυτού με την ανάπτυξη ενός web application στο οποίο θα μπορεί κάποιος χρήστης να γράψει ένα κείμενο και το υλοποιημένο σύστημα να του δημιουργεί ένα σετ από ερωτήσεις και απαντήσεις.

- **Επιθυμητές γνώσεις**: Python, Machine Learning
- **Εμπλεκόμενες Τεχνολογίες – Γνώσεις που θα αποκτηθούν**: Python, Natural Language Understanding and Processing, Question Answering System, web app development
- **Εκτιμώμενος Χρόνος Περάτωσης**: 9 Μήνες
- **Συνεργαζόμενος Ερευνητής**: Νικόλας Μάλαμας
---
## TH-4
**Ανάπτυξη ψηφιακού βοηθού ερωταπαντήσεων για ιστοσελίδες**

Το state of the art στην ανάπτυξη ψηφιακών βοηθών που μπορούν να απαντούν ερωτήσεις (Question Answering virtual assistants) περιλαμβάνει την εκπαίδευση Machine Learning μοντέλων να βρίσκουν την απάντηση χρησιμοποιώντας ως πληροφορία κάθε φορά την ερώτηση και ένα πλαίσιο γνώσης (context). Η προσέγγιση αυτή όμως, περιορίζει σημαντικά την ανάπτυξη τέτοιων βοηθών καθώς απαιτούν το context να είναι αποκλειστικά κείμενο. Αντίθετα, η μεγαλύτερη πηγή πληροφοριών σήμερα είναι το Ίντερνετ. Συνεπώς, στόχος αυτής της διπλωματικής είναι η ανάπτυξη Natural Language μοντέλων που μπορούν να απαντήσουν ερωτήσεις έχοντας ως context το περιεχόμενο από ιστοσελίδες. Επιπλέον, το σύστημα αυτό θα μπορεί να μεταβεί στα λινκ της κεντρικής ιστοσελίδας έτσι ώστε να εξάγει επιπλέον πληροφορίες σχετικές με τις ερωτήσεις. Τέλος, αυτό το σύστημα θα παρουσιαστεί μέσω ενός ψηφιακού βοηθού, είτε web based είτε με την μορφή plugin για κάποιες ιστοσελίδες που θα επιλεγούν.

- **Επιθυμητές γνώσεις**: Python, Machine Learning
- **Εμπλεκόμενες Τεχνολογίες – Γνώσεις που θα αποκτηθούν**: Python, Natural Language Understanding and Processing, Question Answering System, web (browser plugin) development, virtual assistants/chatbots
- **Εκτιμώμενος Χρόνος Περάτωσης**: 9 Μήνες
- **Συνεργαζόμενος Ερευνητής**: Νικόλας Μάλαμας
---
## TH-5
**Ανάλυση Εργασιών Λογισμικού και Σχετικού Κώδικα από Δεδομένα Συστημάτων Ελέγχου Εκδόσεων**

Τα τελευταία χρόνια, ο τρόπος ανάπτυξης λογισμικού ακολουθεί ένα συνεργατικό μοντέλο που βασίζεται σε νέες μεθοδολογίες και προσεγγίσεις, όπως η agile προσέγγιση. Η agile προσέγγιση διέπεται από ένα σύνολο αρχών για την ανάπτυξη λογισμικού του οποίου οι απαιτήσεις αλλάζουν συχνά και βασίζεται στη στενή συνεργασία μεταξύ των ατόμων που απαρτίζουν την ομάδα ανάπτυξης λογισμικού. Οι μηχανικοί της ομάδας ανάπτυξης αναλαμβάνουν συχνά διαφορετικούς ρόλους και καθήκοντα για την αποτελεσματική ανάπτυξη λογισμικού. Σε αυτό το πλαίσιο, κάθε νέο χαρακτηριστικό του προϊόντος και/ή κάθε νέο bug report πρέπει να αναλυθεί ώστε να κατηγοριοποιηθεί βάσει τύπου και προτεραιότητας και να ανατεθεί στον κατάλληλο μηχανικό λογισμικού ώστε να το φέρει εις πέρας (π.χ. να διορθώσει ένα bug). Επιπλέον, για κάθε νέο χαρακτηριστικό είναι χρήσιμο να εκτιμηθούν τα τμήματα κώδικα ή οι περιοχές λογισμικού που αφορά. Σκοπός της διπλωματικής είναι η σχεδίαση ενός συστήματος που θα αυτοματοποιεί τη διαδικασία ανάλυσης εργασιών εστιάζοντας στον κώδικα που αφορά την κάθε εργασία. Τα συστήματα ελέγχου εκδόσεων, όπως π.χ. το GitHub, περιέχουν πλήθος χρήσιμων πληροφοριών που αφορούν τα commits και τα issues (bugs κ.α.) ενός έργου λογισμικού. Έτσι με βάση τις εργασίες σε κάθε αποθετήριο λογισμικού, καθώς και τα σχετικά τμήματα κώδικα που τις αφορούν, είναι εφικτό να αναγνωρίσει κανείς τις σωστές πρακτικές για την καλύτερη διαχείριση της ανάπτυξης λογισμικού.

- **Επιθυμητές γνώσεις**: Καλή γνώση Προγραμματισμού, γνώση Αναγνώρισης Προτύπων, φαντασία και όρεξη για δουλειά
- **Εμπλεκόμενες Τεχνολογίες – Γνώσεις που θα αποκτηθούν**: Εξόρυξη Δεδομένων, Τεχνολογία Λογισμικού, Αναγνώριση Προτύπων
- **Εκτιμώμενος Χρόνος Περάτωσης**: 9 Μήνες
- **Συνεργαζόμενος Ερευνητής**: Θεμιστοκλής Διαμαντόπουλος