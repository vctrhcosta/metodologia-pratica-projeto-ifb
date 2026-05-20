# Prompts Flora — Luminária de Mesa

Fluxo de 6 módulos para geração visual no Flora. Cada módulo entrega uma saída definida que alimenta o próximo. Usar em sequência.

---

## Módulo 1 — Território emocional e tensões

```
I'm designing a premium table lamp (R$900–1800) for a very specific user: Beatriz, 43, architect, lives in Noroeste — Brasília's newest planned neighborhood. She tests material honesty before any aesthetic judgment. Fake finishes (laminate imitating wood, painted plastic imitating metal) are identified in seconds and disqualify the object permanently. She keeps few objects but keeps them for decades. Her apartment is her permanent laboratory.

The lamp is a design gift — bought by someone else (partner, adult child, close friend with equivalent taste), delivered in a context where the box must communicate intention before being opened.

Based on this context, define:
1. The emotional territory this product occupies (3-4 words maximum)
2. Three tensions the product must resolve simultaneously (format: "X without Y" or "X that doesn't sacrifice Y")
3. What this lamp replaces (not physically — what emotional/aesthetic gap it fills in her space)
4. The single moment that determines success or failure (when exactly does Beatriz decide to keep or replace this object?)

Keep the output to under 200 words. No generic design language — be specific to this user in this city.
```

---

## Módulo 2 — Voz, posição e diferenciação

```
Context: premium table lamp, R$900-1800, gift for an architect in Brasília who demands material honesty above all. The emotional territory is [INSERT MODULE 1 OUTPUT].

The competitive landscape:
- Nordic brands (Norm Architects/Hashira, Louis Poulsen/Panthella) own refinement + portability but cannot claim Brazilian territory
- Italian icons (Artemide/Nessino, Flos) own historical authorship but deliver plastic at touch
- National authorship (Fernando Prado/LED'S PLAY T) owns material honesty but lacks sculptural presence

Define:
1. Brand voice on 3 axes: warm↔clinical, minimal↔maximal, artisanal↔engineered. Place this product precisely on each axis with one sentence explaining why.
2. Two value propositions that differentiate from ALL competitors above. Format: "[What we deliver] that [competitor category] cannot." Each must be verifiable by touch or sight in under 3 seconds.
3. One sentence Beatriz would use to describe this lamp to a friend. Not marketing copy — how an architect actually talks about objects she respects.

Output: under 150 words. No adjectives without material evidence.
```

---

## Módulo 3 — Tradução visual (verbal → material)

```
Context: premium Brazilian table lamp. Value propositions: [INSERT MODULE 2 PROPOSITIONS].

Translate each value proposition into physical design language. For each one, name:

- A primary material (specific: "turned freijó heartwood" not "wood")
- A surface texture (what does it feel like at fingertip resolution?)
- A light quality (color temperature, diffusion type, edge behavior)
- A spatial relationship (how does the object occupy the 30cm radius around it?)
- A joint logic (how do materials meet? flush, revealed, overlapping, floating?)

Then define three visual principles that connect all answers above into a coherent formal language. Format each as a verb phrase: "expose the joint", "let weight be visible", etc.

Constraints:
- No material that simulates another material
- Every material must age predictably over 10+ years without degrading
- The lamp must have formal interest when OFF (it exists 14 hours/day without emitting light)
- Production must be viable with Brazilian suppliers in small batches

Output: structured list, under 250 words.
```

---

## Módulo 4 — Conceito e metáfora (filtrada)

```
Context: Brazilian premium table lamp. Visual principles: [INSERT MODULE 3 PRINCIPLES]. Materials: [INSERT MODULE 3 MATERIALS].

The lamp lives in Brasília — a city founded as a design project. Lucio Costa's vocabulary of rigorous geometry and formal clarity shaped the visual culture here. The user is an architect who lives inside this vocabulary daily.

Propose 3 conceptual anchors for the lamp's formal identity. For each:
- Name the concept in 2-3 words
- Describe what structural/natural/architectural element it references
- Explain the shared logic between that element and the lamp's core tension (material honesty + sculptural presence)
- Describe the silhouette it implies (height, proportions, gesture)

Rules:
- No flowers, no organic metaphors disconnected from Brasília's architectural vocabulary
- No literal references to Niemeyer or modernist icons (columns, curves, palaces)
- Each concept must be buildable with the materials defined in Module 3
- Prefer structural logic over decorative symbolism

Then choose the strongest. Explain in one sentence why it wins over the other two.

Output: under 300 words.
```

---

## Módulo 5 — Direção de cena (composição)

```
Context: [INSERT CHOSEN CONCEPT FROM MODULE 4]. Materials: [INSERT MODULE 3 MATERIALS]. The lamp is [INSERT SILHOUETTE DESCRIPTION].

Describe a product photography scene that communicates "material honesty with sculptural presence" without any text. This is how Beatriz first encounters the lamp — in an editorial image shared by a friend or seen in a design publication.

Define:
- Background: material, color, texture (must contrast with lamp materials without competing)
- Surface the lamp sits on: material, finish, what else shares the surface (one object maximum)
- Lighting: direction, quality (hard/soft), color temperature, what it reveals about the lamp's material
- Camera angle: height relative to lamp, distance, what detail is sharpest in focus
- The single detail that communicates the value proposition in one glance (the "proof point" visible in the image)
- What is deliberately NOT shown or cropped (create desire through absence)

Constraints:
- No white void / studio limbo
- The environment must be plausibly Brasília (light quality, materials, architectural hints)
- The lamp must be OFF in this image — its formal presence must justify itself without light
- No props that explain the lamp (no books about design, no architect tools)

Output: one paragraph of scene description, under 150 words. Write it as a brief to a photographer, not as marketing copy.
```

---

## Módulo 6 — Geração visual

```
[INSERT MODULE 5 SCENE DESCRIPTION AS WRITTEN].

Style: editorial product photography. Natural light from left, late afternoon in Brasília (golden, horizontal, casting long defined shadows). Shot on medium format, shallow depth of field with the [INSERT PROOF POINT DETAIL] in critical focus.

Materials rendered with physical accuracy: [INSERT SPECIFIC MATERIALS FROM MODULE 3] — show grain, show weight, show how light interacts with the surface at a tangent angle.

The image should feel like a page from Wallpaper* or Dezeen, not a product listing. One object, one environment, one story.

Do NOT include: text, logos, humans, packaging, other products, pure white backgrounds, floating objects, or any element that reads as CGI rather than photographed.
```

---

## Notas de uso

- Cada módulo depende do anterior. Não pule.
- Copie a saída relevante do módulo anterior no campo [INSERT...] do próximo.
- Se a saída de um módulo parecer genérica, peça ao Flora para ser mais específico antes de avançar ("Be more specific about X — what exactly does that look like at 30cm viewing distance?").
- O Módulo 4 é o mais crítico. Se o conceito não convencer, não adianta gerar imagem bonita.
- Adapte o Módulo 6 conforme o sistema de geração do Flora aceitar (se tiver limite de caracteres, priorize a cena + materiais + o que evitar).
