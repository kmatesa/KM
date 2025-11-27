Kreiraj repozitorij na github-u
Kreiraj folder u vscode
Naprvi git clone kako bi se povezao github i projekt:
Git clone https://github.com/kmatesa/KM.git
Kreiranje quasar projekta:
 npm install -g @quasar/cli - instalacija
npm init quasar  - kreiranje foldera(odabrati ESLint, Axios, Vue-i18n)
quasar dev - pokretanje Quasar aplikacije
Kreiranje stranice:
quasar new page ImePage.vue 
dodaj u routes.js rutu i u MainLayout.vue link za stranicu(#/)
u components -> EssentialLink.vue iz _blank u _parent
<h1>Naslov</h1>
Naredbe za slanje na github:
Git add * 
Git commit -m „Naziv izmjene“
Git push
Git config user.name „kmatesa“
Git config user.email „email“
Git pull 
BACKEND:
Npm install naziv_paketa
Npm install express cors body-parser mysql 
Npm install -g nodemon
Pokretanje: nodemon index.js
Testiranje na </RESTED>
