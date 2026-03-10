# HE-Mostar-Data-Science-Project
Analiza rada agregata HE Mostar pomoću strojnoga učenja - Kolegij: Podatkovna znanost i inženjerstvo.
# Analiza i predviđanje rada HE Mostar (2026)

**Autor:** Antonio Ćorić  
**Kolegij:** Podatkovna znanost i inženjerstvo  

## Opis projekta
Ovaj projekt istražuje operativne podatke hidroelektrane Mostar koristeći metode strojnog učenja. Cilj je predvidjeti stanje rada agregata na temelju senzorskih očitanja (snaga, napon, struja).

## Korištene tehnologije
* **Jezik:** Python 3.14.3
* **Biblioteke:** Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib
* **Okruženje:** Visual Studio Code / Google Colab

## Rezultati modeliranja
Uspoređeno je pet različitih modela, a najbolji rezultat postigao je **Random Forest Classifier**:
* **Točnost (Accuracy):** 99.17%
* **F1-Score:** 0.99 (izvrsna ravnoteža preciznosti i odziva)

## Kako pokrenuti?
1. Klonirajte repozitorij.
2. Učitajte `HE_Mostar_2026.csv`.
3. Pokrenite `HE_Mostar_Analiza.ipynb`.
