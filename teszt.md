# Teszt

Név: Csupor Nándor 

## Kérdések:

1. Mit értünk egy `commit` alatt, mit tartalmaz?
Változtatás, tetszőlegesméterű lehet, de kb 1 commit 1 logikai változtatás legyen
1. Mi a különbség a `fetch` es `pull` git parancsok között?
A fetch csak lekéri a távoli repo-ból a változtatásokat, de nálam nem módosít semmit
a pull lehúzza a változtatásokat.
1. Mi a három állapota file-oknak git szempontjából, milyen parancsokkal mozgatjuk ezek között?
untracked, modified, staged - add, commit, remove 
1. Mi a különbség a `git checkout origin/feature` és a `git checkout feature` parancsok között?
Az első az originen belül lévő feature-re branch-re vált, a másik a sima feature branch-re.
1. Mi történik, ha valaki más is módosította a file-t amin dolgozunk és mit tudunk tenni ilyenkor?
conflict lesz, amit majd fel kell oldani.
1. Mi az a `HEAD` és mi a jelentősége?
Legutolsó commit-ra való hivatkozás
1. Mi a célja a branch-elésnek?
Hogy több irányba haladhasson a project. Később el lehet dönteni hogy mit rakunk bele a Main-be.
1. Hogyan lehet összehasonlítani file-ok állapotait, mire tudjuk még ezt a kimenetet használni?
git diff - Változtatásokat megmutatja a working directory + index, branchek, fájlok, commit-ok között.
1. Hogy lehet megnézni egy repo történetét, milyen eszközeink vannak ebben való keresésre?
git log - grep-el lehet keresni.
1. Melyik git parancsot használnád, hogy megtudd milyen állapotban van épp a repo?
git status.

