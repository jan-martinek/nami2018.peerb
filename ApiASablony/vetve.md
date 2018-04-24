### Větvení v gitu

S větvemi jsme se potkali v předchozí lekci, nyní se na ně podíváme blíže a systematicky.

Když chcete navrhnout změnu v cizím repozitáři na Githubu, běžně již pracujete s *forky*. Při týmové spolupráci pak zpravidla vlastník týmového repozitáře nasdílí svůj repozitář přímo ostatním. To však  neznamená, že budou všichni házet kód do repozitáře hlava-nehlava.

**Pracovní workflow zůstává velmi podobné:** spolupracovníci pracují ve vlastní *větvi* (*branch*), kde zpracují konkrétní úpravu a následně posílají pull request z této větve. Větve fungují na první pohled podobně jako *forky*, nicméně díky tomu, že existují ve stejném repozitáři, umožňují více (v tomto kurzu však nicméně oceníme především jednodušší práci a přehled o změnách na jednom místě). 

Je rozumné omezit přístup do hlavní větve (nejspíše jste si všimli označení *master*, což je právě název větve) a stanovit podmínky přijetí pull requestu — jako např. určitý počet recenzí (reviews). 

Všichni pak pracují stejně, ať už jde o vlastníka repozitáře nebo ostatní členy týmu — vytvoří větev, tam nasází commity se změnami a vyžádá si kontrolu pull requestu od jiného člena týmu: tomuto se říká „code review“ (v češtině se zatím neujal žádný přeložený ekvivalent). Při týmové práci je tak zajištěno, že každou změnu omrkne několik členů týmu (dle počtu vyžadovaných hodnocení).

Ve výsledku tak práce na konkrétní úpravě vypadá následovně:

- (Mám nasdílený týmový repozitář nebo jsem jeho vlastníkem.)
- Chci udělat změnu, tak si pro ni založím větev v klonu, který mám u sebe v počítači. Takové větvi se říká „feature branch“, protože v ní chcete vytvořit kód pro konkrétní požadovanou vlastnost (feature).
- Zpracuji změny a commitnu je do této větve (najednou anebo v několika commitech).
- Větev pushnu na Github a vytvořím pull request do hlavní větve (zpravidla *master*).
- Jiný člen týmu projde mé změny na stránce pull requestu a změny ohodnotí. Následně on/a nebo někdo jiný sloučí změny a pull request uzavře.
- Větev vytvořenou pro danou změnu je nyní možné smazat. (Větev zůstane v počítači všech, kteří s ní pracovali, protože vždy pracujete s konkrétní větví v konkrétním umístění.)

> Pozn. Při práci v konkrétní větvi může spolupracovat i více lidí, ale je potřeba, aby se domluvili na způsobu spolupráce.

Tento postup budete v následujících týdnech opakovat často, proto si jej zažijte.
