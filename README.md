## **Soal 1 - Jamur Beracun 🍄**

UCI (_University of California, Irvine_) menyediakan dataset karakteristik sampel dari sekitar 23 spesies jamur, yang diambil dari buku ilmiah _The Audubon Society Field Guide_ dan _North American Mushroom_. Setiap spesies diidentifikasi sebagai jamur yang dapat dimakan atau jamur beracun yang tidak dapat dikonsumsi. Unduh dataset __*mushrooms.csv*__ [di sini](./datasets/mushrooms.csv). Data terdiri atas 23 kolom dengan detail categorical value sebagai berikut.
- __classes__: e = edible, p = poisonous
- __cap-shape__: b = bell, c = conical, x = convex, f = flat, k = knobbed, s = sunken
- __cap-surface__: f = fibrous,g = grooves, y = scaly, s = smooth
- __cap-color__: n = brown, b = buff, c = cinnamon, g = gray, r = green, p = pink, u = purple, e = red, w = white,y = yellow
- __bruises__: t = bruises, f = no
- __odor__: a = almond, l = anise, c = creosote, y = fishy, f = foul, m = musty, n = none, p = pungent, s = spicy
- __gill-attachment__: a = attached, d = descending, f = free, n = notched
- __gill-spacing__: c = close, w = crowded, d = distant
- __gill-size__: b = broad, n = narrow
- __gill-color__: k = black, n = brown, b = buff, h = chocolate, g = gray, r = green, o = orange, p = pink, u = purple, e = red, w = white, y = yellow
- __stalk-shape__:  e = enlarging, t = tapering
- __stalk-root__: b = bulbous, c = club, u = cup, e = equal, z = rhizomorphs, r = rooted, ? = missing
- __stalk-surface-above-ring__: f = fibrous, y = scaly, k = silky, s = smooth
- __stalk-surface-below-ring__: f = fibrous, y = scaly, k = silky, s = smooth
- __stalk-color-above-ring__: n = brown, b = buff, c = cinnamon, g = gray, o = orange, p = pink, e = red, w = white, y = yellow
- __stalk-color-below-ring__: n = brown, b = buff, c = cinnamon, g = gray, o = orange, p = pink, e = red, w = white, y = yellow
- __veil-type__: p = partial, u = universal
- __veil-color__: n = brown, o = orange, w = white, y = yellow
- __ring-number__: n = none, o = one, t = two
- __ring-type__: c = cobwebby, e = evanescent, f = flaring, l = large, n = none, p = pendant s = sheathing, z = zone
- __spore-print-color__: k = black, n = brown, b = buff, h = chocolate, r = green, o = orange, u = purple, w = white, y = yellow
- __population__: a = abundant, c = clustered, n = numerous, s = scattered, v = several, y = solitary
- __habitat__: g = grasses, l = leaves, m = meadows, p = paths, u = urban, w = waste, d = woods

Buatlah sebuah file notebook (_.ipynb_) yang menjelaskan tata cara pembuatan model machine learning untuk mengklasifikasikan mana jamur yang dapat dikonsumsi dan mana jamur yang beracun berdasarkan dataset tersebut. Anda bebas menggunakan model apapun, sertakan pula evaluation metrics dan plot ROC AUC-nya.

__Requirements:__

- Buat sebuah file __notebook__ (_.ipynb_).
- Unduh & gunakan dataset [__*mushrooms.csv*__](./datasets/mushrooms.csv).
- Buat model yang dapat mengklasifikasikan jamur beracun dan tidak. Algoritma model bebas.
- Tentukan & hitung metriks evaluasi model.
- Gambarkan plot ROC AUC model.
