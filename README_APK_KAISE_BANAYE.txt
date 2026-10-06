SAHAJ ACADEMY - APK KAISE BANAYE (GitHub se, free, kuch install nahi karna)

1) github.com par free account banayein. Phir "New repository" dabayein.
   Naam: sahaj-academy, Private rakhein, "Create repository" dabayein.

2) Is zip ko unzip karein. Mac par hidden folder dikhane ke liye Finder mein Cmd + Shift + . dabayein.
   Repository page par "uploading an existing file" par click karein aur unzip kiye folder ke ANDAR ki
   saari cheezein drag karein: www, assets, .github, package.json, capacitor.config.json, .gitignore.
   Neeche "Commit changes" dabayein.

   Agar .github folder upload nahi hua:
   "Add file" > "Create new file" dabayein, naam ke box mein ye likhein:
   .github/workflows/build-apk.yml
   phir build-apk.yml file ka poora text paste karke "Commit changes" dabayein.

3) Upar "Actions" tab kholein. "Build Sahaj Academy APK" chalna shuru ho jayega (5 se 10 minute).
   Na chale to us workflow par click karke "Run workflow" dabayein.

4) Green tick aane par us run par click karein. Neeche "Artifacts" mein "Sahaj-Academy-APK" download karein.
   Zip kholne par app-debug.apk milegi.

5) APK ko WhatsApp ya cable se phone mein bhejein aur kholein. Phone "Install unknown apps" allow karne ko
   bolega, allow karke install kar lein.

Baad mein PDF ya app badalna ho:
- www/pdfs mein nayi PDF daalein ya www/index.html badlein, GitHub par commit karein.
- Actions apne aap nayi APK bana dega.

Dhyan dein:
- Ye APK seedha students ko bhejne ke liye hai. Play Store ke liye alag signed build aur developer account chahiye.
- OTP abhi demo hai (screen par dikhta hai). Student ka data us phone mein hi save hota hai.
