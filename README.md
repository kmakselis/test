# Mano pirmoji GIT repozitorija

Ši repozitorija yra skirta tam, kad išmokti naudotis GIT **projektų versijavimo kontrolės komandinės eilutės sąsaja (GIT CLI)**. Tam reikės parsisiųsti ir instaliuoti:
https://git-scm.com/downloads

## Repozitorijos parsiuntimas
1. Atsidarykite GIT CLI (GIT bash).
2. Naudodami komandą <cd> pakeiskite savo darbinę kategoriją į tą, į kurią norite parsisiųsti repozitoriją
3. Parsiųskite repozitoriją: https://github.com/kmakselis/test
4. Pakeiskite darbinę kategoriją į parsiųstos repozitorijos kategoriją
cd test

## Pagrindinės komandos
**git add** -> failų paruošimas patvirtinimui
    **git add <failo-pavadinimas>** -> prideda failą nurodytu pavadinimu
    **git add .** -> prideda visus pakitusius failus

**git diff** - skirtumas tarp dviejų failų ar dvijeų to paties failo versijų
    **git diff <failo-pavadinimas>** -> failo nurodytu pavadinimu pakitimai nuo paskutinio commit'o 

**git status** -> parodo pakitusių failų būseną

**git branch** -> komanda, kuri naudojama operacijoms su šakomis
    **git branch -a** -> parodo visas parsiųstas šakas ir  šiuo metu aktyvią šaką

**git commit** -> komanda, skirta užtvirtinti projekto pakitimui
    **git commit -m 'žinutė apibūdinti pakitimą'**

**git push** -> komanda, skirta pavieršinti commit'us į atitinkamą globalią šaką


git add . -> git commit -m 'description' -> git push