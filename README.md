# 🕌 Muslim App — تطبيق المسلم

Application islamique complète — Coran, Invocations et Dhikr.

🔗 **[➡️ Ouvrir l'application](https://lem2003.github.io/MuslimApp/)**

---

## 📱 Aperçu

> Une application web gratuite et open-source pour la communauté musulmane.
> Lisez le Coran, apprenez les invocations quotidiennes et comptez vos dhikr — le tout dans une seule application.

---

## ✨ Fonctionnalités

### 📖 Le Saint Coran
- Texte arabe (Uthmani) verset par verset
- Audio intégré avec 10 récitateurs
- Traduction en français et anglais
- Navigation par **Juz** (30) ou par **Sourate** (114)
- Recherche de sourates
- Répétition de verset (pour la mémorisation)
- Lecture automatique des versets
- Suivi de progression (Juz lus)
- Liens directs vers un Juz ou une Sourate

### 🤲 Invocations & Adhkar
- 10 catégories d'invocations
- Adhkar du matin et du soir (textes complets)
- Adhkar après la prière
- Duas du sommeil, du réveil, du repas, du voyage
- Duas de protection et de demande de pardon
- Duas pour les parents
- Duas tirées du Coran
- Texte arabe + traduction française
- Sources authentiques (Coran & Sunnah)

### 📿 Dhikr & Tasbih
- Compteur de dhikr interactif (type tasbih numérique)
- SubhanAllah (33x), Alhamdulillah (33x), Allahu Akbar (34x)
- Istighfar (100x), Salawat (100x)
- Dhikr après la prière, du matin, du soir
- Dhikr à tout moment
- **Gros bouton compteur** facile à utiliser
- Barre de progression par dhikr
- Célébration quand tous les dhikr sont terminés 🎉
- Sauvegarde automatique de la progression
- Réinitialisation individuelle ou globale

### 🌟 Général
- 🌙 Verset du jour sur la page d'accueil
- 🎙️ Test du récitateur avant d'écouter le Coran
- ⚙️ Paramètres accessibles depuis l'accueil (récitateur & traduction)
- 📱 Responsive (mobile, tablette, desktop)
- 📴 Mode hors ligne (PWA)
- 🔔 Notifications toast
- ⌨️ Raccourcis clavier (Espace = lecture, Flèches = navigation, Échap = retour)
- 📊 Statistiques sur l'accueil (Juz lus, Adhkar faits)

---

## 🎙️ Récitateurs disponibles

| Récitateur | Style |
|-----------|-------|
| Mishary Rashid Alafasy | Murattal |
| Abdul Basit Abdul Samad | Murattal |
| Abdurrahman As-Sudais | Murattal |
| Mahmoud Khalil Al-Husary | Murattal |
| Muhammad Siddiq Al-Minshawi | Mujawwad |
| Ali Al-Hudhaify | Murattal |
| Muhammad Ayyoub | Murattal |
| Muhammad Jibreel | Murattal |
| Hani Ar-Rifai | Murattal |
| Ibrahim Al-Akhdar | Murattal |

---

## 🌍 Traductions disponibles

| Langue | Traducteur |
|--------|-----------|
| 🇫🇷 Français | Muhammad Hamidullah |
| 🇬🇧 English | Sahih International |
| 🇬🇧 English | Pickthall |

---

## 🛠️ Technologies

- **HTML5 / CSS3 / JavaScript** — Vanilla (aucun framework)
- **API** — [Al Quran Cloud API](https://alquran.cloud/api)
- **Audio** — Fourni directement par l'API (URLs garanties)
- **Hébergement** — GitHub Pages
- **PWA** — Service Worker pour le mode hors ligne

---

## 📁 Structure du projet
📁 MuslimApp/
├── 📄 index.html → Page d'accueil + Paramètres + Test récitateur
├── 📄 quran.html → Section Coran (Juz & Sourates)
├── 📄 duas.html → Section Invocations & Adhkar (textes)
├── 📄 Dhikrs.html → Section Dhikr & Tasbih (compteurs)
├── 📄 style.css → Styles partagés
├── 📄 manifest.json → Configuration PWA
├── 📄 sw.js → Service Worker (mode hors ligne)
└── 📄 README.md → Ce fichier



---

## 🔗 Liens directs

Vous pouvez partager un lien direct vers un Juz ou une Sourate :

| Lien | Description |
|------|-------------|
| [Juz 1](https://lem2003.github.io/MuslimApp/quran.html?juz=1) | Premier Juz du Coran |
| [Juz 30](https://lem2003.github.io/MuslimApp/quran.html?juz=30) | Juz Amma |
| [Al-Fatiha](https://lem2003.github.io/MuslimApp/quran.html?surah=1) | Sourate Al-Fatiha |
| [Al-Baqarah](https://lem2003.github.io/MuslimApp/quran.html?surah=2) | Sourate Al-Baqarah |
| [Yasin](https://lem2003.github.io/MuslimApp/quran.html?surah=36) | Sourate Yasin |
| [Al-Mulk](https://lem2003.github.io/MuslimApp/quran.html?surah=67) | Sourate Al-Mulk |
| [Al-Kahf](https://lem2003.github.io/MuslimApp/quran.html?surah=18) | Sourate Al-Kahf |
| [Duas du Matin](https://lem2003.github.io/MuslimApp/duas.html?cat=morning_adhkar) | Adhkar du matin |
| [Dhikr Prière](https://lem2003.github.io/MuslimApp/Dhikrs.html?cat=after_salah) | Tasbih après salat |

---

## 🚀 Fonctionnalités à venir (In Shaa Allah)

- [ ] 🕌 Horaires de prière (basés sur la localisation)
- [ ] 🧭 Direction de la Qibla
- [ ] 🔖 Marque-pages personnalisés (dernière lecture)
- [ ] 🎨 Thèmes de couleurs (clair / sombre / sépia)
- [ ] 📊 Statistiques de lecture détaillées
- [ ] 🌐 Plus de langues de traduction (turc, espagnol, ourdou...)
- [ ] 📥 Téléchargement hors ligne des sourates
- [ ] 🔔 Rappels de lecture quotidienne
- [ ] 📖 Mode Mushaf (affichage page par page)
- [ ] 🎓 Mode Hifz (mémorisation avec répétition)

---

## 💡 Contribuer

Ce projet est une **Sadaqa Jariya** (charité continue).
Toute contribution est la bienvenue :

1. ⭐ Mets une étoile au projet
2. 🍴 Fork le repository
3. 🐛 Signale un bug dans les [Issues](https://github.com/lem2003/MuslimApp/issues)
4. 💡 Propose une fonctionnalité
5. 📤 Soumets une Pull Request
6. 📢 Partage l'app avec ta famille et tes amis

---

## 🤲 Dua

<div align="center">

**رَبَّنَا تَقَبَّلْ مِنَّا إِنَّكَ أَنتَ السَّمِيعُ الْعَلِيمُ**

*Notre Seigneur, accepte ceci de notre part. Tu es certes l'Audient, l'Omniscient.*

---

**اللَّهُمَّ اجْعَلِ الْقُرْآنَ رَبِيعَ قَلْبِي وَنُورَ صَدْرِي**

*Ô Allah, fais du Coran le printemps de mon cœur et la lumière de ma poitrine.*

---

**اللَّهُمَّ انْفَعْنِي بِمَا عَلَّمْتَنِي وَعَلِّمْنِي مَا يَنْفَعُنِي وَزِدْنِي عِلْمًا**

*Ô Allah, fais-moi profiter de ce que Tu m'as enseigné, enseigne-moi ce qui m'est utile et accrois mes connaissances.*

</div>

---

## 📜 Licence

Ce projet est libre et open-source. Utilisez-le, partagez-le et améliorez-le pour la communauté musulmane.

---

<div align="center">

Made with ❤️ and ☕ by **Mouhamadou**

*Un projet Sadaqa Jariya pour la Ummah* 🕌

**جزاكم الله خيرا — Qu'Allah vous récompense en bien**

</div>
