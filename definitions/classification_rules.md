# Classification Rules for 12-Seasonal Color Analysis

These rules define undertones, contrast, and hue characteristics for accurate AI classification.
Use these as anchor definitions when comparing uploaded selfies against the reference faces and palette images.

---

## 🌸 SPRING PALETTES — Warm + Clear + Bright Undertones

### **True Spring**
- Undertone: Warm, golden, peachy.
- Contrast: Medium.
- Skin: Warm ivory to light golden beige, glows under warm light.
- Hair: Golden blonde, coppery light brown, warm chestnut.
- Eyes: Clear green, light hazel, warm blue.
- Color bias: Bright and warm tones.
- Avoid: Muted, ashy, or cool gray colors.

### **Bright Spring**
- Undertone: Warm-neutral, very clear.
- Contrast: High between skin and features.
- Skin: Neutral-warm, clear.
- Hair: Golden blonde, auburn, medium brown.
- Eyes: Bright blue, topaz, green.
- Color bias: Clear, vivid, warm colors.
- Avoid: Dusty or muted hues.

### **Light Spring**
- Undertone: Warm, soft.
- Contrast: Low.
- Skin: Fair to medium, peach undertones.
- Hair: Light golden blonde to copper.
- Eyes: Light blue, green, or hazel.
- Color bias: Warm pastels, light hues.
- Avoid: Dark, heavy colors.

---

## 🌊 SUMMER PALETTES — Cool + Muted + Gentle Undertones

### **True Summer**
- Undertone: Cool, rosy, or beige with blue undertones.
- Contrast: Medium.
- Skin: Fair to medium-cool.
- Hair: Ashy blonde to medium brown.
- Eyes: Cool blue, gray, soft green.
- Color bias: Muted cool tones, dusty rose, soft periwinkle.
- Avoid: Warm or orange-based hues.

### **Soft Summer**
- Undertone: Neutral-cool to olive.
- Contrast: Low-medium.
- Skin: Neutral beige, olive beige.
- Hair: Ash brown, soft muted tones.
- Eyes: Muted hazel, gray-green, soft brown.
- Color bias: Dusty, grayish tones, mauve, taupe.
- Avoid: Very bright or dark colors.

### **Light Summer**
- Undertone: Cool, light, delicate.
- Contrast: Low.
- Skin: Fair-cool to light neutral.
- Hair: Pale ash blonde to light brown.
- Eyes: Light blue, gray, or green.
- Color bias: Soft pastels, airy light colors.
- Avoid: Heavy or intense shades.

---

## 🍂 AUTUMN PALETTES — Warm + Muted + Rich Undertones

### **True Autumn**
- Undertone: Warm, golden, bronze.
- Contrast: Medium.
- Skin: Warm beige, golden tan.
- Hair: Golden blonde to auburn.
- Eyes: Olive, golden brown, warm hazel.
- Color bias: Earthy, rich, warm tones — rust, camel, olive.
- Avoid: Cool or icy tones.

### **Soft Autumn**
- Undertone: Neutral-warm.
- Contrast: Low-medium.
- Skin: Sandy beige to soft golden.
- Hair: Light brown with muted gold.
- Eyes: Soft green, hazel, brown.
- Color bias: Warm-muted shades, moss, taupe, peach.
- Avoid: Harsh or saturated colors.

### **Dark Autumn**
- Undertone: Warm, deep.
- Contrast: High.
- Skin: Golden bronze, deep olive.
- Hair: Dark brown to black-brown.
- Eyes: Dark hazel, deep green, warm brown.
- Color bias: Deep warm tones, teal, mahogany, forest green.
- Avoid: Cool pastel colors.

---

## ❄️ WINTER PALETTES — Cool + High Contrast + Intense

### **True Winter**
- Undertone: Cool, clear.
- Contrast: High.
- Skin: Fair to deep cool.
- Hair: Dark brown to black.
- Eyes: Cool hazel, icy blue, deep brown.
- Color bias: Bright cool tones, cobalt, icy pink, black and white.
- Avoid: Warm or muted shades.

### **Bright Winter**
- Undertone: Cool, neutral-cool.
- Contrast: Highest.
- Skin: Cool beige to fair porcelain.
- Hair: Medium to dark brown or black.
- Eyes: Bright blue, dark brown, cyan.
- Color bias: Bright, high-intensity cool hues.
- Avoid: Warm yellow or brown.

### **Dark Winter**
- Undertone: Cool, deep.
- Contrast: Dramatic.
- Skin: Neutral-cool to olive.
- Hair: Dark brown to black.
- Eyes: Deep brown, dark blue, olive.
- Color bias: Jewel tones — emerald, navy, burgundy.
- Avoid: Light warm tones.

---

## ⚙️ CLASSIFICATION LOGIC SUMMARY

1. Identify undertone temperature (warm vs. cool) based on hue averages (skin vs. background).
2. Measure contrast between skin, hair, and eyes (ΔE in LAB color space).
3. Cross-check undertone + contrast result against this rule table.
4. Match similarity with closest reference_faces images.
5. Choose the seasonal palette with the smallest aggregate difference.

