# Mano pirmoji GIT repozitorija

## Repozitorijos parsiuntimas
git clone <repozitorijos-nuoroda>

## Pagrindinės komandos
git add -> failų paruošimas patvirtinimui
    git add <failo-pavadinimas> -> prideda failą nurodytu pavadinimu
    git add . -> prideda visus pakitusius failus

git diff - skirtumas tarp dviejų failų ar dvijeų to paties failo versijų
    git diff <failo-pavadinimas> -> failo nurodytu pavadinimu pakitimai nuo paskutinio commit'o 

git status -> parodo pakitusių failų būseną

git branch -> komanda, kuri naudojama operacijoms su šakomis
    git branch -a -> parodo visas parsiųstas šakas ir  šiuo metu aktyvią šaką

git commit -> komanda, skirta užtvirtinti projekto pakitimui
    git commit -m 'žinutė apibūdinti pakitimą'

git push -> komanda, skirta pavieršinti commit'us į atitinkamą globalią šaką


add -> commit -> push