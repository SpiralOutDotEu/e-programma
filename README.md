# e-Πρόγραμμα
Ένα αρχείο HTML που μπορούν να χρησιμοποιήσουν γονείς, μαθητές και καθηγητές για να φτιάξουν ένα εύχρηστο πρόγραμμα των ηλεκτρονικών μαθημάτων με τους συνδέσμους για το κάθε `meeting room`.

Με τον τρόπο αυτό, θα έχουν οι μαθητές εναν έυκολο τρόπο να μπαίνουν στα `meeting room` των καθηγητών τους χωρίς να χάνουν χρόνο, ακόμα και όσοι δεν έχουν την ευχέρεια των υπολογιστών.

 Παράλληλα μπορεί να γίνει μια καλή `άσκηση` για τους μαθήτες της πληροφορικής και να φτιάξουν την πρώτη τους σελίδα.

 [Live prewiew](https://htmlpreview.github.io/?https://raw.githubusercontent.com/SpiralOutDotEu/e-programma/main/index_sample.html)

 [PDF version](https://github.com/SpiralOutDotEu/e-programma/blob/main/e-%CE%A0%CF%81%CF%8C%CE%B3%CF%81%CE%B1%CE%BC%CE%BC%CE%B1.pdf?raw=true)

![e-programma](https://github.com/SpiralOutDotEu/e-programma/blob/main/e-programma.png?raw=true)
![webex-sample](https://github.com/SpiralOutDotEu/e-programma/blob/main/webex-sample.jpg?raw=true)

To `e-programma` είναι συμβατό με κινητά ή ταμπλετ:

![mobile](https://github.com/SpiralOutDotEu/e-programma/blob/main/e-programma-mobile.png?raw=true)

## Οδηγίες χρήσης

1. Κατεβάστε το αρχείο [main.zip](https://github.com/SpiralOutDotEu/e-programma/archive/main.zip), αποσυμπιέστε το αρχείο `index.html` στον υπολογιστή σας και μετονομάστε το σε κάτι χρήσιμο όπως `A1-16-11-2020.html` αλλά διατηρείστε την κατάληξη `.html`

2. Ανοίξτε το αρχείο που αποθηκέυσατε με ένα απλό επεξεργαστή κειμένου όπως το σημειωματάριο (notepad). Αν θέλετε κάποιον πιο εξειδικευμένο επεξεργαστή δοκιμάστε δωρεάν τον [Visual Studio Code](https://code.visualstudio.com/).

3. Αλλάξτε στις γραμμές της κεφαλίδας `(44-53)` τα στοιχεία του σχολείου, του τμήματος και της ημερομηνίας έκδοσης:
```html
<li class="nav-item">
    <a class="nav-link" href="#">Xο Γυμνάσιο Νέας Γενιάς</a>
</li>
<li class="nav-item">
    <a class="nav-link" href="#">Α1</a>
</li>
<li class="nav-item">
    <a class="nav-link" href="#">16/11/2020</a>
</li>
```
4. Αλλάξτε τις ώρες του προγράμματος στις γραμμές `(62-75)`:
```html
<th scope="col">Ημέρα</th>
<th scope="col">1η ώρα <p>8:15-9:00</p>
</th>
<th scope="col">2η ώρα <p>9:00-9:45</p>
</th>
<th scope="col">3η ώρα <p>10:00-10:45</p>
</th>
<th scope="col">4η ώρα <p>10:45-11:30</p>
</th>
<th scope="col">5η ώρα <p>11:45-12:30</p>
</th>
<th scope="col">6η ώρα <p>12:30-13:15</p>
</th>
<th scope="col">7η ώρα <p>13:30-14:10</p>
</th>
```

5. Το πρόγραμμα της κάθε ημέρας, βρίσκεται μεταξύ καθε ζευγαριού κωδικών `<tr>` και `</tr>` που συμβολίζουν μια γραμμή στον πίνακα: 
```html
<tr>
    <th scope="row">Δευτέρα</th>
    <td>Μάθημα<p><i><i><a href="link">Καθηγητής</a></i></i>
        </p>
    </td>
    <td>Μάθημα<p><i><a href="link">Καθηγητής</a></i>
        </p>
    </td>
    <td>Μάθημα<p><i><a href="link">Καθηγητής</a></i>
        </p>
    </td>
    <td>Μάθημα<p><i><a href="link">Καθηγητής</a></i>
        </p>
    </td>
    <td>Μάθημα<p><i><a href="link">Καθηγητής</a></i>
        </p>
    </td>
    <td>Μάθημα<p><i><a href="link">Καθηγητής</a></i>
        </p>
    </td>
    <td>Μάθημα<p><i><a href="link">Καθηγητής</a></i>
        </p>
    </td>
</tr>
```
Αλλάξτε στις αντίστοιχες γραμμές τις λέξεις `Μαθημα`,`link`, `Καθηγητής` με τα αντίστοιχα στοιχεία, όπως παρακάτω:
```html
<td>Μάθηματικά
    <p>
        <i><a href="https://minedu-secondary.webex.com/meet/Pythagoras">
        Πυθαγόρας Σάμιος
        </a></i>
    </p>
</td>
```
6. Αποθηκέυστε το αρχείο και ανοίξτε το με έναν browser όπως ο `Chrome`, `Firefox`, `Edge`. Μπορείτε επίσης να το εκτυπώσετε σε `pdf` απο τον browser. 

7. Το αρχείο μπορεί να σταλεί απευθείας μέσω e-mail, viber κτλ. και να είναι πλήρως λειτουργικό. Μπορεί επίσης να αναρτηθεί σε κάποιον `προστευμένο` ιστότοπο. Ο ιστότοπος θα πρέπει να είναι `προστατευμένος` για να μην υπάρχει διαρροή προσωπικών δεδομένων και απειλή `spam`.

## Αναφορές

* Για βασικές γνώσεις `HTML` δείτε [εδώ](https://www.w3schools.com/html/default.asp).
* Το `e-programma` χρησιμοποιεί το [bootstrap](https://getbootstrap.com/) ώς θέμα εμφάνισης και προσαρμογής σε οθόνες. Μπορείτε να μάθετε περισσότερα [εδώ](https://www.w3schools.com/bootstrap4/default.asp).
