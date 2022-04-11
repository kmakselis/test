# Mano pirmoji GIT repozitorija

Ši repozitorija yra skirta tam, kad išmokti naudotis GIT **projektų versijavimo kontrolės komandinės eilutės sąsaja (GIT CLI)**. Tam reikės parsisiųsti ir instaliuoti:
https://git-scm.com/downloads

## Repozitorijos parsiuntimas
1. Atsidarykite GIT CLI (GIT bash).
2. Naudodami komandą **&lt;cd&gt;** pakeiskite savo darbinę kategoriją į tą, į kurią norite parsisiųsti repozitoriją
3. Parsiųskite repozitoriją: https://github.com/kmakselis/test
4. Pakeiskite darbinę kategoriją į parsiųstos repozitorijos kategoriją
cd test

## Pagrindinės komandos
1. **git add** -> failų paruošimas patvirtinimui
    -  **git add &lt;failo-pavadinimas&gt;** -> prideda failą nurodytu pavadinimu
    -  **git add .** -> prideda visus pakitusius failus

2. **git diff** - skirtumas tarp dviejų failų ar dvijeų to paties failo versijų
    -  **git diff &lt;failo-pavadinimas&gt;** -> failo nurodytu pavadinimu pakitimai nuo paskutinio commit'o 

3. **git status** -> parodo pakitusių failų būseną

4. **git branch** -> komanda, kuri naudojama operacijoms su šakomis
    -  **git branch -a** -> parodo visas parsiųstas šakas ir  šiuo metu aktyvią šaką

5. **git commit** -> komanda, skirta užtvirtinti projekto pakitimui
    -  **git commit -m 'žinutė apibūdinti pakitimą'**

6. **git push** -> komanda, skirta pavieršinti commit'us į atitinkamą globalią šaką


git add . -> git commit -m 'description' -> git push