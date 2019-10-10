# Raster και Raster Stack στην R


**[Εργαστήριο Χωρικής Ανάλυσης, Γεωγραφικών Πληροφοριακών Συστημάτων και Θεματικής Χαρτογραφίας](http://www.gislab.gr/)**

Το τρέχον αποθετήριο αποτελεί το υλικό για την παρουσίαση του εργαστηρίου (workshop) "Raster και Raster Stack στην R" στο συνέδριο [FOSSCOMM 2019](https://2019.fosscomm.gr/).

## Στόχος

Στόχος του εργαστηρίου είναι η εξοικείωση του χρήστη με το πακέτο [raster](https://cran.r-project.org/web/packages/raster/index.html) της R το οποίο προσφέρει την δυνατότητα 
ανάγνωσης ψηφιδωτών δεδομένων (raster) και επεξεργασίας τους ([crop](https://www.rdocumentation.org/packages/raster/versions/2.9-5/topics/crop), [reclassify](https://www.rdocumentation.org/packages/raster/versions/2.9-5/topics/reclassify), [reproject](https://www.rdocumentation.org/packages/raster/versions/2.9-5/topics/projectRaster), [resample](https://www.rdocumentation.org/packages/raster/versions/2.9-5/topics/resample) κτλ.).

Επιπλέον, θα επικεντρωθούμε στην κλάση [raster stack](https://www.rdocumentation.org/packages/raster/versions/2.9-5/topics/stack) η οποία δημιουργεί συστοιχίες ψηφιδωτών δεδομένων, κατάλληλες για χρονοσειρές και πολυκαναλικές εικόνες.

Η διεξαγωγή του εργαστηρίου θα γίνει μέσω παραδειγμάτων και με την χρήση δεδομένων νυκτερινών φώτων [DMSP-OLS Nighttime Lights Time Series (Stable Lights Version 4)](https://ngdc.noaa.gov/eog/dmsp/downloadV4composites.html).
Θα προηγηθεί μια [σύντομη παρουσίαση](https://github.com/kokkytos/rworkshop/blob/master/presentation.pdf) των βημάτων και της διαδικασίας ώστε οι χρήστες να αποκτήσουν μια σύντομη αλλά περιεκτική εικόνα του στόχου του εργαστηρίου και των δυνατοτήτων που προσφέρει ο προγραμματισμός με την R.


## Προαπαιτούμενα

* το πακέτο στατικής ανάλυσης **R** (https://www.r-project.org/) <sup>[1](#myfootnote1)</sup>
* το περιβάλλον εργασίας **Rstudio** (https://www.rstudio.com/) <sup>[1](#myfootnote1)</sup>
* οι βιβλιοθήκες **raster,ggplot2,rasterVis,rgdal,leaflet**.
Για την εγκατάστασή τους δώστε στο Console του rstudio την εντολή:

`install.packages(c("raster","ggplot2","rasterVis","rgdal","leaflet"),dependencies=T)`

* **R Notebook** και **raster δεδομένα** από το τρέχον αποθετήριο του workshop.
* Προαιρετικά το **git** (https://git-scm.com/). Για να λάβετε το περιεχόμενο του workshop μέσω του *git* δώστε την εντολή:
`git clone https://github.com/kokkytos/rworkshop.git`

Eναλλακτικά το αποθετήριο είναι διαθέσιμο και σε [συμπιεσμένη μορφή](https://github.com/kokkytos/rworkshop/archive/master.zip).

<a name="myfootnote1"><sup>[1]</sup></a> Προτείνεται η προεγκατάσταση. Στο εργαστήριο θα επιλυθούν προβλήματα.

Το πλήρες περιβάλλον στο οποίο εκτελέστηκε ο τρέχων κώδικας R περιγράφεται στο αρχείο [sessionInfo.txt](sessionInfo.txt) 

## Ύλη εργαστηρίου

Ο κώδικας και τα βήματα του εργαστηρίου διατίθενται σε [R notebook](workshop.Rmd) (και σε [html έκδοση](https://kokkytos.github.io/rworkshop/workshop.html)).

## Ερωτήσεις/Παρατηρήσεις

Τυχόν ερωτήσεις ή παρατηρήσεις θα υποβάλλονται στην [σχετική ενότητα του αποθετηρίου](https://github.com/kokkytos/rworkshop/issues).


## Συγγραφείς

* [Λιάκος Λεωνίδας](https://gr.linkedin.com/in/leonidasliakos)

* [Σταθάκης Δημήτρης](https://gr.linkedin.com/in/dstath)

