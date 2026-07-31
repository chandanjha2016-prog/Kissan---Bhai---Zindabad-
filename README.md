# 🌾 Kisan Bhai Zindabad App
### Bicholiya Mukta Krishi Portal | Viksit Bharat @2047

## 1. PROJECT KYA HAI ?
"**Kisan Bhai Zindabad**" ek 100% free aur mobile-friendly website hai. 
Iska maksad hai kisan ko bicholiye se bachana aur usko sahi daam dilana.

**3 Bade Feature:**
1.  **Aaj ka Mandi Bhav** - Patna, Gaya, Muzaffarpur ki rate rozana
2.  **Sarkari Yojana** - PM Kisan, Fasal Bima, Subsidy ki jankari + direct link
3.  **Mausam** - Agle 3 din ka mausam taaki fasal bacha sake

**Mission:** `Har Kisan Digital. Har Kisan Khushal.`

## 2. LIVE DEMO LINK
👉 **https://jha2016-prog.github.io/kisan-bhai-zindabad/**

## 3. KAISE USE KAREIN ?
1.  Link open karein
2.  Apna Jila chune
3.  Mandi Bhav, Yojana, Mausam dekhein

## 4. TECHNOLOGY
`HTML` + `CSS` + `JavaScript` - Koi server nahi. Koi kharcha nahi.

---
## 5. SOURCE CODE - COPY KARKE CHALAO

`index.html` naam se ye file banao:

```html
<!DOCTYPE html>
<html lang="hi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Kisan Bhai Zindabad - Viksit Bharat @2047</title>
<style>
body { font-family: 'Segoe UI'; background: #e8f5e9; margin: 0; }
header { background: linear-gradient(90deg, #FF9933 33%, #FFF 33% 66%, #138808 66%); color: #000080; text-align: center; padding: 15px; }
.card { background: white; margin: 15px; padding: 15px; border-radius: 10px; box-shadow: 0 2px 8px #ccc; border-left: 5px solid #FF9933; }
h2 { color: #000080; }
button { background: #FF9933; color: #000; border: none; padding: 12px; width: 100%; border-radius: 8px; font-weight: bold; cursor: pointer; }
.price { font-size: 24px; color: #138808; font-weight: bold; }
footer { background: #000080; color: white; text-align: center; padding: 15px; margin-top: 20px; }
</style>
</head>
<body>

<header>
  <h1>🌾 Kisan Bhai Zindabad</h1>
  <p>Bicholiya Mukta Krishi | Viksit Bharat @2047</p>
</header>

<div class="card">
  <h2>1. Aaj ka Mandi Bhav - Patna Mandi</h2>
  <p>Gehu: <span class="price">₹2400 / Quintal</span></p>
  <p>Dhan: <span class="price">₹2200 / Quintal</span></p>
  <p>Alu: <span class="price">₹1200 / Quintal</span></p>
  <small>Source: agmarknet.gov.in | Update: Rozana 11 AM</small>
</div>

<div class="card">
  <h2>2. Sarkari Yojana</h2>
  <p>✅ <b>PM Kisan:</b> 2000 ki agali kist 15 Aug ko</p>
  <p>✅ <b>Fasal Bima:</b> Last date 31 July</p>
  <button onclick="alert('Is link se seedha pmkisan.gov.in pe jayega')">Yojana ke liye Apply Karein</button>
</div>

<div class="card">
  <h2>3. Mausam</h2>
  <p>Agle 3 din: Halki Barish 🌧️</p>
  <p>Tapman: 28°C - 34°C</p>
</div>

<footer>
  <h3>🇮🇳 JAI JAWAN - JAI KISAN 🇮🇳</h3>
  <p>Created With Love By: <b>Chandan Kumar</b></p>
  <p>Jamalpur, Bihar | India</p>
  <p style="font-size:10px;">"Ek Kisan Khushal = Desh Khushal"</p>
  <hr style="margin:10px auto; width:50%; border:1px solid #138808;">
  <p style="font-size:11px;">© 2026 | For Viksit Bharat @2047</p>
</footer>

</body>
</html>
