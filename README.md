pwa/
اﻟﺘﻄﺒﯿﻖ اﻟﺮﺋﯿﺴﻲ ← nizam-v99.html ──├
)اﻻﺳﻢ، اﻷﯾﻘﻮﻧﺔ، اﻷﻟﻮان( PWA إﻋﺪادات ← manifest.json ──├
├── sw.js ← Service Worker (ﻟﻠﻌﻤﻞ Offline)
أﯾﻘﻮﻧﺎت ﺑﺄﺣﺠﺎم ﻣﺨﺘﻠﻔﺔ ← /icons ──├
│ ├── icon-72.png
│ ├── icon-96.png
│ ├── icon-128.png
│ ├── icon-144.png
│ ├── icon-152.png
│ ├── icon-192.png
│ ├── icon-384.png
│ └── icon-512.png
└── README.md
)ٮ,ﻠڡ , ﺎﺋى 4 HTTPS ،ﻣﺤ # ﺎٮ3ى 4 ( GitHub Pages اﻟٮ3ﺸﺮ ﻋﲆ
:اﻟﺤ % ﻄوات
GitHub أٮ12 ﻣﺴٮ-ﻮدﻋاً ﺣ ( ﺪٮ&ﺪاً ﻋﲆ .1
github.com → New repository اذﻫﺐ إﻟﻰ
nizam-asra :اﺳﻤﻪ ﻣٮ*ﻼً
)اﻟﻤﺤ 2 ﺎٮ:ى 8 GitHub Pages ﻣﻄﻠﻮب ﻟـ( Public اﺣ 2 ﻌﻠﻪ
ارڡ 2 ﻊ اﻟﻤﻠڡ 2 ﺎت .2
git clone https://github.com/USERNAME/nizam-asra
cp -r pwa/* nizam-asra/
cd nizam-asra
git add .
git commit -m "PWA v99"
git push
GitHub Pages ڡ 2 ﻌ ّ ﻞ .3
Settings → Pages → Source: main branch → / (root)
اٮ:ٮ@ﻄ : ﺮ دڡ@ٮ?ڡ @ ٮ@ٮ?ﻦ
https://USERNAME.github.io/nizam-asra/nizam-v99.html :اﻟراٮ2ﻂ
ٮ,ثٮ#ٮ?ﺖ اﻟٮ,ﻄٮ#ٮ?ﻖ ﻋﲆ اﻟﺤ # ﻬﺎز
iPhone/iPad (Safari):
Safari اڡ : ٮ@ﺢ اﻟراٮ2ﻂ ڡ:ى 8 .1
اﺿﻌ O ﻂ زر اﻟﻤﺸﺎرﻛﺔ .2
”إﺿﺎڡ : ﺔ إﻟﻰ اﻟﺸﺎﺷﺔ اﻟﺮﺋٮ?ﺴٮ?ﺔ“ / ”Add to Home Screen“ اﺣ : ٮ@ﺮ .3
ﺳٮ?ﻄ : ﻬﺮ كﺄٮ?ڡ @ ﻮٮ:ﺔ ٮ@ﻄٮ2ٮ?ﻖ ﻋﺎدي .4
Android (Chrome):
Chrome اڡ : ٮ@ﺢ اﻟراٮ2ﻂ ڡ:ى 8 .1
ٮ@ﻠڡ @ ﺎﺋٮ?اً ”Add to Home Screen“ ﺳٮ@ﻄ : ﻬﺮ رﺳﺎﻟﺔ .2
”ٮ@ثٮ2ٮ?ﺖ اﻟٮ@ﻄٮ2ٮ?ﻖ“ / ”Install App“ → ⋮ أو: اﻟڡ @ ﺎﺋﻤﺔ .3
ﺳٮ?ﻄ : ﻬﺮ كﺄٮ?ڡ @ ﻮٮ:ﺔ ٮ@ﻄٮ2ٮ?ﻖ ﻋﺎدي .4
اﻟﻤٮ?زات ٮ#ﻌﺪ اﻟٮ,ثٮ#ٮ?ﺖ
اﻟﺤﺎﻟﺔ اﻟﻤٮ#ﺰة
)Offline( ٮ?ﻌﻤﻞ ٮ2ﺪون إٮ:ٮ@ﺮٮ:ﺖ
أٮ?ڡ @ ﻮٮ:ﺔ ﻋﲆ اﻟﺸﺎﺷﺔ اﻟﺮﺋٮ?ﺴٮ?ﺔ
ﺷﺎﺷﺔ ﰷﻣﻠﺔ ٮ2ﺪون ﺷريﻂ اﻟﻤٮ@ﺼڡ : ﺢ
اﻟٮ2ٮ?ﺎٮ:ﺎت ﻣﺤڡ : ﻮﻃ : ﺔ ﻋﲆ اﻟﺤ 2 ﻬﺎز
Androidو iOS ٮ?ﻌﻤﻞ ﻋﲆ
App Store ﻻ ٮ?ﺤٮ@ﺎج
ﻣﻼﺣﻄ 3 ﺎت ﻣﻬﻤﺔ
ﻋﲆ ﺣ 2 ﻬﺎزك ڡ : ڡ @ ﻂ — ﻻ ﳾء ٮ?ُﺮﺳ َ ﻞ ﻷي ﺣ : ﺎدم localStorage اﻟﺤ 2 ﺼﻮﺻٮ&ﺔ: اﻟٮ2ٮ?ﺎٮ:ﺎت ٮ@ُﺤ : زlن ڡ:ى 8
اﻟٮ2ﺴﺦ اﻻﺣٮ-ٮ&ﺎطى E : اﺳٮ@ﺤ : ﺪم زر “ٮ:ﺴﺦ اﺣٮ@ٮ?ﺎطى 8 ” داﺣ : ﻞ اﻟٮ@ﻄٮ2ٮ?ﻖ ﻟﺤڡ : ﻆ ٮ2يﺎٮ:ﺎٮ@ﻚ
