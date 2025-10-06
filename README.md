# Image Stitching

## Opis projekta

U ovom projektu sistematično je prikazan kompletan proces nadovezivanja preklapajućih slika u panoramu.
Kroz Jupyter svesku `Image_Stitching.ipynb` postupno se obrađuju ključni koraci procesa opisom standardnih algoritama sa
implementacijom određenih delova mahom oslanjanjem na openCV biblioteku za obradu slika.
Opisani koraci: detekcija ključnih tacaka (SIFT algoritam), izračunavanje i uparivanje deskriptora (FLANN sa KNN i Lowe's ratio testom),
procena transformacije koja dovodi slike u isti referentni sistem, poravnavanje i stapanje slika u celinu, a zatim izdvajanje
upotrebljivog pravougaonog rezultata.
Na samom kraju dat je praktični prikaz spajanja više slika u jednu zajedničku panoramu kroz korišćenje openCV funkcija.

## Potrebni paketi

- **numpy**
- **matplotlib**
- **opencv**

## Korišćena literatura

1. [Richard Szeliskim (2006), _Image Alignment and Stitching: A Tutorial_](https://pages.cs.wisc.edu/~dyer/cs534/papers/szeliski-alignment-tutorial.pdf)
2. [Yung-Yu Chuang, _Image stitching_](https://www.csie.ntu.edu.tw/~cyy/courses/vfx/23spring/lectures/handouts/lec07_stitching_4up.pdf)
3. [Shree K. Nayar, (2021), _Image stitching, Columbia University (Video)_](https://www.youtube.com/watch?v=J1DwQzab6Jg&list=PL2zRqk16wsdp8KbDfHKvPYNGF2L-zQASc)
