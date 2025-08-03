
# 🌐 Website Spec Document for FBC BC

## ✝️ Project Overview:
Create a **static, single-page website** for a small, Southern Baptist church named **FBC BC**, located in **southeast Missouri (Dunklin and Pemiscot counties)**. The site should reflect the church’s warmth, simplicity, and strong community values. It must follow **SEO best practices**, meet **WCAG AAA accessibility standards**, and be suitable for **static hosting** (e.g., Cloudflare Pages).

---

## 🧭 Purpose:
- Share basic info about the church (service times, location, beliefs)
- Communicate a **welcoming, community-first identity**
- Ensure maximum accessibility for all users
- Rank well in **local search results**

---

## 🧱 Technical Requirements:

- **Framework:** Astro (preferred static site generator)
- **Hosting:** Cloudflare Pages (100% static)
- **No JavaScript or CMS required for content**
- **Minimal dependencies for performance and security**
- **Use JavaScript only for current year in footer**

---

## 🧑‍🦯 Accessibility (WCAG AAA):
- Color contrast must meet AAA guidelines
- Fully semantic HTML with ARIA support where necessary
- Fully keyboard navigable
- Skip-to-content link
- Proper alt text on all images
- Clear focus styles
- Resize text up to 200% without content loss
- No flashing or auto-playing content

---

## 🔍 SEO Best Practices:
- Clear, descriptive `<title>` and `<meta description>`
- Semantic heading hierarchy (H1–H2–H3)
- Mobile-friendly, responsive layout
- Open Graph and Twitter meta tags
- Schema.org structured data:
  - `Organization`
  - `PlaceOfWorship`
- Favicon and Apple Touch icon
- Fast load speed

---

## 🎨 Design Style:
- Simple, clean, and welcoming
- Sans-serif font (system stack or Inter/Lato)
- One-column layout on mobile
- AAA-compliant color palette (high contrast, friendly tone)
- Placeholder images (to be replaced later)

---

## 📄 Page Content Layout

### 1. **Hero Section**
- **Church Name:** FBC BC
- **H1 Headline:**  
  _“A Welcoming Community Rooted in Faith”_
- **H2 Subheadline:**  
  _“Serving families and friends throughout Dunklin and Pemiscot Counties”_
- Call-to-action button: **“Join Us This Sunday”** (scrolls to service times)

---

### 2. **About the Church**
- Short description (~100–150 words):  
  FBC BC is a small Southern Baptist church committed to serving southeast Missouri. We exist to glorify God through worship, teaching, and fellowship. Whether you're new to church or have been attending for years, you're welcome here.

---

### 3. **Service Times**
- **Sundays:** 11:00 AM & 5:00 PM  
- **Wednesdays:** 5:00 PM (Prayer Service)

---

### 4. **Location**
- **Address:**  
  151 W Second St  
  Bragg City, MO 63827

- Include an **accessible static map image** with alt text  
- Optional text link to [Google Maps](https://maps.google.com/?q=151+W+Second+St,+Bragg+City,+MO+63827)

---

### 5. **What to Expect**
- FAQ-style brief content:  
  - _What should I wear?_ “Whatever makes you comfortable—most people dress casually.”  
  - _Do you have childcare?_ “We’re a family-oriented church where all are welcome.”  
  - _Is it okay to just visit?_ “Absolutely—we’d love to meet you.”

---

### 6. **Our Beliefs**
- Short statement:  
  FBC BC is a Southern Baptist congregation. We believe in the Bible as the Word of God and Jesus Christ as Lord and Savior. Our mission is to love God, serve others, and grow together in faith.

---

### 7. **Stay Connected**
- **Facebook Page:**  
  [facebook.com/share/g/1BpyQAzRiH](https://www.facebook.com/share/g/1BpyQAzRiH/?mibextid=wwXIfr)

---

### 8. **Footer**
- Church name and address repeated  
- Copyright © <script>document.write(new Date().getFullYear());</script>  
- Back to top anchor link  
- Optional: Accessibility Statement link

---

## 🖼 Assets (Placeholders for Now):
- Logo or stylized church name in text
- 1–2 placeholder images: outside of a rural church, warm congregation, etc.
- Static map image of address location

---

## ✅ Completed Details:
- ✅ Church Name: FBC BC  
- ✅ Region: Dunklin and Pemiscot counties, Missouri  
- ✅ Address: 151 W Second St, Bragg City, MO 63827  
- ✅ Service Times: Sunday 11 AM & 5 PM, Wednesday 5 PM  
- ✅ No contact form or email  
- ✅ Facebook Page: https://www.facebook.com/share/g/1BpyQAzRiH/?mibextid=wwXIfr  
- ✅ Denomination: Southern Baptist  
- ✅ Use placeholder images  
- ✅ Use Astro as static site generator  
- ✅ Footer shows current year via JavaScript
