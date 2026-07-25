# **Why Image Generation Has Been Struggling for Your Project**

## **1. World-scale consistency is extremely hard for models**

You ask for:

- Ashroot → semi-blighted ancient forest
    
- The Veil → harmonics, sigils, instabilities
    
- Concord architecture → grounded, BG3-style
    
- Cindersong motifs → rebel markings, flame motifs
    
- Rootspire → hybrid magic/functional tree city
    
- Maps → geospatial logic + lore-correct symbols
    
- NPCs → unique racial traits + custom magic “echoes”
    

These are all **custom**. AI has _no_ baseline for:

- “Cindersong aesthetic”
    
- “Concord architecture”
    
- “Rootspire Tree-City design language”
    
- “Blue-flame genasi echo of Fergie”
    
- “Ashroot’s wounded–semi-blighted look”
    

So the model invents or drifts, because it cannot internally reference your world the way a human artist would.

**Solution:** Short, grounded descriptions + anchor to real media references (“BG3 cinematic realism,” “Arcane-inspired magic effects”).

---

## **2. Maps stress every weak point of current models**

Models are poor at:

- stable geography
    
- accurate labels
    
- consistent symbols
    
- orthographic views
    
- keeping roads/rivers where you want
    
- respecting your text constraints
    

If you give them too much detail, they hallucinate or “approximate.”

**Solution:**  
**Prompt maps like loose concept art**, not functional cartography. Avoid:

- more than 4 landmarks
    
- any exact distances
    
- more than 1–2 labelled paths
    

Then annotate manually.

---

## **3. Anything with text or sigils is inherently inconsistent**

Requests like:

- “Include the Cindersong three-ring sigil”
    
- “Add Concord banners”
    
- “Put these labels on the map”
    

→ These break image models.  
High chance of warped or wrong symbols.

**Solution:**  
Generate **clean art with NO writing**, then add text/symbols in Obsidian, Photoshop, Figma, or PPTX afterward.

---

## **4. Location prompts can get too “conceptual”**

When requests include:

- “hybrid of old magic and Concord engineering”
    
- “semi-blighted treetop city with harmonics visible in the walls”
    
- “Arcane x BG3 mood with sigils reacting to the Veil”
    

The model doesn’t know what those actually _look like_.

**Solution:**  
Break each into:  
→ **Architecture shape**  
→ **Primary materials**  
→ **Lighting**  
→ **Environment mood**  
→ **One magic effect max**

---

# **How to Dramatically Improve Outputs**

Here is the exact framework that works best for your world.

---

# **A. NPC Image Prompts (Your Biggest Struggle)**

### **Formula**

**[Race/Class basics] + [Physical anchors] + [Distinctive flame/sigil/magic element] + [Clothing style grounded in real-world analog] + [Camera + Lighting + BG3 realism]**

### **Example** – _Maria Zurita, blue-flame echo of Fergie_

**Prompt Template for You to Reuse:**

> Baldur’s Gate 3–style portrait of a blue-flame fire genasi woman, early thirties, sharp eyes, ember-freckles glowing beneath the skin. Her hair rises like smokeless cobalt fire. Clothing inspired by desert nomad robes mixed with Concord military tailoring—layered fabrics, muted charcoal tones, scorched edges. A faint harmonic sigil glows at her collarbone. Half-body shot, three-quarter angle, soft rim-light, dark forest background with hints of the Blighted Ashroot.

**Tips:**

- NEVER say “blue fire genasi version of Fergie.” Models freak out with “version of.”
    
- Always specify **one** magic marker (blue fire, ember freckles, floating sigil).
    
- Anchor clothing to real analogs (“desert nomad,” “Renaissance,” “mariner,” etc.)
    

---

# **B. Location Art (Rootspire, Orrenval, rebel camps)**

### **Formula**

**[Structure type] + [Major material] + [One magical element] + [Mood/lighting] + [1–2 landmarks] + BG3 realism**

### **Example – Rootspire Arrival**

> Aerial view of Rootspire, a vast tree-city spiraling around a colossal living trunk. Platforms and bridges grown from natural wood, reinforced with Concord steel struts that glint in the afternoon haze. Small lantern spores float through the air like dim fireflies. A blighted patch at the eastern roots shows sickened bark and faint violet sigils. Warm golden lighting, grounded cinematic realism, Baldur’s Gate 3 style.

**Tips:**

- Limit yourself to **two architectural ideas maximum** (natural wood + Concord metal).
    
- Include **one** Veil/magic effect (floating spores, faint sigils, harmonic flicker).
    
- Avoid describing more than one blighted area per prompt.
    

---

# **C. Maps (Ashroot, Rootspire region, paths)**

### The single biggest improvement:

**Ask for “hand-drawn concept map, unlabeled, rough, sketch-like.”**

Models handle **“impressionistic geography”** 100× better.

### **Formula**

**[Hand-drawn sketch] + [top-down or isometric] + [3–4 major locations] + [1 river or 1 road or 1 border] + [simple shading/ink] + BG3 parchment mood**

### **Example – Ashroot Forest Map**

> Hand-drawn parchment-style concept map of the Ashroot Forest, top-down view. A single winding river cuts from north to south. To the west, a solitary path leads toward a distant city. To the north, jagged boundary markings indicate the Riven Marches. To the east, a colossal tree is sketched—Rootspire. Add two smaller branching trails and hints of blighted patches shown as darkened brush strokes. Rough ink lines, uneven shading, minimal detail, no text.

**Tips:**

- Never ask for more than **one** river.
    
- Never ask for more than **three** major locations.
    
- Never ask for more than **three** paths.
    
- Always ask for **no text**.
    

---

# **D. Environmental Scenes (encounters, groves, rituals)**

### **Formula**

**[Position of characters] + [one core magical phenomenon] + [terrain anchors] + [lighting] + [BG3 realism]**

### Example – Stone Monolith Sigil Grove

> Forest clearing in the Ashroot, dusk light filtering through twisted branches. A stone monolith stands at the center, its face engraved with a Cindersong-style circular sigil glowing faint ember-orange. Faint harmonic tendrils drift upward like mist disturbed by sound. Mossy ground, scattered fallen leaves, cool blue ambient shadows. Baldur’s Gate 3 cinematic realism.

**Tips:**

- Don’t describe the party.
    
- Don’t give more than one sigil.
    
- Choose a single time of day.
    
- Anchor the magic effect to something physical (fog, sound, fire).
    

---

# **E. General Best Practices for Your World**

### **1. One magic effect per image**

Your setting has:

- Veil tears
    
- Sigils
    
- Harmonics
    
- Blue fire
    
- Blight rot
    
- Light spores
    
- Warp-wood  
    Models can’t do more than 1–2 of these consistently.
    

### **2. Keep prompts 2–4 sentences max**

Longer prompts → models ignore half your instructions.

### **3. If you want **consistency**, reuse the same structure**

“BG3 realism + 3/4 angle + soft rim-light + shallow depth of field”  
→ becomes your campaign’s visual “brand.”

### **4. Generate _safe_ base art, then edit**

Maps especially benefit from:

- Add labels in Obsidian/PPTX/Figma
    
- Add sigils manually
    

### **5. Separate lore from visuals**

Never include:

- emotional tone
    
- narrative consequences
    
- political context
    
- philosophical descriptions
    

Models can’t visually interpret them and will hallucinate details.