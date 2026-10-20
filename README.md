# Glimglee Products Catalogue & E-Commerce Asset Portal

Welcome to the **Glimglee Products** repository. This repository contains the complete product catalog, high-resolution lifestyle photography, official specification Word documents (`.docx`), and an interactive web portal for browsing and managing 48 curated e-commerce products.

---

## 🌟 Overview & Highlights

* **Total Products:** 48 Active Products
* **Product Categories:**
  * 🪔 **Traditional Jhumkas (ET Series):** 10 Products (Oxidized Silver, German Silver, Temple Peacock)
  * 💎 **Kundan & Chandbali (E / e Series):** 26 Products (Ruby, Emerald, Navratan, Turquoise, Agate, Filigree, Druzy)
  * 🕯️ **Scented Candles (C Series):** 2 Products (Handcrafted 3D Peony & Rose Floating Candles, Luxury Soy Gift Set)
  * ⌚ **Luxury Bracelet Watches (W Series):** 2 Products (Rose Gold & Rhodium Silver Floral Crystal Watches)
  * 🌸 **Botanical Resin Pendants (P Series):** 2 Products (Real Preserved Daisy & Pink Nigella in Pearl Chains)
  * 🎁 **Home Accents & Novelty Gifts:** 6 Products (Mandala Mirror `M1`, Heart Hamper `H1`, Photo Frame `PF1`, Couple Statues `S1` & `S2`, Resin Pooja Thali `T1`)

---

## 📁 Repository Structure

Each product folder follows a standardized structure:
```
product/
├── C1/
│   ├── [High-Res Photos].png
│   └── Product_Details_C1.docx
├── ET1/
│   ├── [High-Res Photos].png
│   └── Product_Details_ET1.docx
├── ...
├── index.html            # Interactive Web Catalogue & 1-Click Copy Portal
├── products_data.js      # Structured JSON Database of all 48 products
└── README.md
```

---

## 📄 Word Documents (`.docx`) Contents

Every product folder contains a dedicated specification sheet with:
1. **Product Title:** SEO-optimized marketplace title (Amazon / Flipkart / Shopify / Myntra).
2. **Taxation & Compliance:** Exact 8-digit HSN Code, applicable GST rate %, and CGST/SGST/IGST breakdown.
3. **Descriptions:** Short description (meta/app listing) and comprehensive detailed description.
4. **Key Features (A+ Bullets):** 5 structured Amazon-standard bullet points with bold headers.
5. **Technical Specifications Table:** 12–15 field grid covering materials, dimensions, weights, closure/mounting, occasions, country of origin, and package contents.
6. **Care Instructions:** Material-specific preservation guidelines.
7. **SEO Keywords:** High-intent backend search tags.

---

## 🌐 Interactive Web Portal

To view the interactive catalogue portal with photo galleries and 1-click copy buttons:
1. Double click on `index.html` to open directly in any web browser.
2. Or run a local HTTP server:
   ```bash
   python3 -m http.server 8080
   ```
   Then open `http://localhost:8080` in your browser.
