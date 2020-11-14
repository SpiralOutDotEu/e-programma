# e-Πρόγραμμα
Ένα αρχείο HTML που μπορούν να χρησιμοποιείσουν γονείς, μαθητές και καθηγητές για να φτιάξουν ένα εύχρηστο πρόγραμμα των ηλεκτρονικών μαθημάτω ενώ παράλληλα μπορεί να γίνει μια καλή άσκηση για τους μαθήτες της πληροφορικής.

Με τον τρόπο αυτό, θα έχουν οι μαθητές εναν έυκολο τρόπο να μπαίνουν στα `meet room` τον μαθημάτων τους χωρίς να χάνουν χρόνο, ακόμα και όσοι δεν έχουν ακόμα την ευχαίρεια των υπολογιστών.

![e-programma](https://github.com/SpiralOutDotEu/e-programma/blob/main/e-programma.png?raw=true)

To `e-programma` είναι συμβατό και με κινητά ή ταμπλετ:
![mobile](https://github.com/SpiralOutDotEu/e-programma/blob/main/e-programma-mobile.png?raw=true)

## Οδηγίες χρήσης

1. Κατεβάστε το αρχείο [index.html.zip](https://minhaskamal.github.io/DownGit/#/home?url=https://github.com/SpiralOutDotEu/e-programma/blob/main/index.html), αποσυμπιέστε το αρχείο `index.html` στον υπολογιστή σας και μετονομάστε το σε κάτι χρήσιμο όπως `A1-16-11-2020.html` αλλά διατηρείστε την κατάληξη `.html`

2. Ανοιξτε το αρχείο που αποθηκέυσατε με ενα απλό επεξεργαστή κειμένου όπως το σημειωματάριο (notepad). Αν θέλετε κάποιον πιο εξειδικευμένο επεξεργαστή δοκιμάστε δωρεάν τον [Visual Studio Code](https://code.visualstudio.com/).

3. Αλλάξτε στις γραμμές τις κεφαλίδας `(44-53)` τα στοιχεία του σχολείου, του τμήματος και της ημερομηνίας έκδοσης:
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
4. Αλλάξτε τις ώρες του προγράμματος στίς γραμμές `(62-75)`:
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

5. Το πρόγραμμα τις κάθε ημέρας, βρίσκεται μεταξύ καθε ζευγαριού κωδικών `<tr>` και `</tr>` που συμβολίζουν μια γραμμή στον πίνακα: 
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
Αλλάξτε στις αντιστοιχες γραμμές τις λέξεις `Μαθημα`,`link`, `Καθηγητής` με τα αντιστοιχα στοιχεία, όπως παρακάτω:
```html
<td>Μάθηματικά
    <p>
        <i><a href="https://minedu-secondary.webex.com/meet/Pythagoras">
        Πυθαγόρας Σάμιος
        </a></i>
    </p>
</td>
```
6. Αποθηκέυστε το αρχείο και ανοίξτε το με εναν browser όπως ο `Chrome`, `Firefox`, `Edge`.



