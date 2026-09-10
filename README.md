# YT Playlist Player (Android)

Ek simple Android app jo aapke diye YouTube links ko sequence mein play karti hai —
har video ko ek fix duration (default 20 min, per-video override kar sakte hain) ke liye
chalati hai, phir automatically agla video play karti hai.

## Kaise chalayein

1. **Android Studio** open karein (latest stable version, Hedgehog ya newer).
2. `File > Open` se ye poora `YTPlaylistPlayer` folder select karein.
3. Gradle sync khud ho jayega (internet chahiye pehli baar).
4. Ek Android phone/emulator connect karein (min Android 6.0 / API 23).
5. ▶ Run dabayein.

App khulte hi agar playlist khaali hai to top-right ⚙ (gear) button dabayein,
links add karein, phir wapas aa jayein — pehla video khud play hone lag jayega.

## Features jo already hain

- YouTube links (normal, shorts, youtu.be, koi bhi format) ya sirf video ID daal sakte hain.
- Default duration set kar sakte hain (e.g. 20 min), ya har video ke liye alag duration.
- Bottom overlay mein live countdown timer + "Next ▶" button.
- Agar asal video timer se chhota hai, to wo loop ho kar timer poora hone tak chalta rahega.
- Timer khatam hote hi agla video khud load ho jata hai (playlist end pe wapas shuru se).
- Fullscreen support (YouTube ke apne fullscreen button ya rotate karne par).
- Playlist aur settings phone ki local storage mein save rehti hain (app band karke
  dobara kholne par bhi yaad rehti hain).

## Aage aap ye bhi add karwa sakte hain (bata dijiye, kar dunga)

- **Shuffle / Loop toggle** – random order ya sirf ek playlist baar-baar.
- **Drag-and-drop reorder** – playlist mein videos ki tarteeb change karna.
- **Import poori YouTube playlist** ek playlist URL se (saare videos khud add ho jayen).
- **Resume position** – agar app beech mein band ho jaye, wahin se shuru ho.
- **Background/lock-screen controls** – jaise music player (play/pause/next from notification).
- **Picture-in-picture mode** – doosri app use karte hue chhota video chalta rahe.
- **Multiple named playlists** – jaise "Kids", "News", "Documentaries" alag-alag sets.
- **Auto-start on boot / schedule** – kisi waqt par khud playlist shuru ho jaye.
- **Export/Import playlist as file** – doosre phone par copy karna aasan ho.
- **Dark/Light theme toggle**, bigger font mode for seniors.

## Zaroori note

Ye app YouTube ka official **IFrame Player API** use karti hai — matlab video ke
saath normal ads bhi chalti hain aur kuch bhi download/strip nahi ho raha. Bas
playback ka control (kab kaunsa video, kitni der) app apne paas rakhti hai. Isi
wajah se ye YouTube ke Terms of Service ke mutabiq hai. Agar app ko Play Store
par publish karna ho to Google ki review guidelines bhi follow karni hongi.
