## Modeling Ilocano Enclitic Particles as an Electronic Lexicon


## Project Description
This project aims to build digital resources for natural languages spoken in the Cordillera Administrative Region (CAR) and neighboring regions of the Philippines. It contributes to language preservation, documentation, and the development of tools for natural language processing (NLP), particularly in support of governance and social institutions.

### Objectives
- Construct **electronic lexicons** for selected local languages.
- Collect and digitize **raw linguistic resources** (e.g., documents, song lyrics, articles, social media data).
- Develop or prototype **NLP-based tools** or submit a **journal-style report** discussing tool design.
- Support **eGovernance** through accessible, localized language technology.

---

## Data Sources
The lexicon data is compiled from a range of digitized linguistic resources, including:  

- **[Blogs/Articles](https://drive.google.com/drive/folders/1YDuQ-2aLtz8E66xN4IbeEE2l1fpPygJA?usp=drive_link)** – Online texts, essays, and community blog posts  
- **[Social Media](https://drive.google.com/drive/folders/1z5y7vpXse7qMetqM_ZuOoy5ntMDZuP03?usp=drive_link)** – Posts, comments, and interactions collected from social media platforms  
- **[Others](https://drive.google.com/drive/folders/1rrA_YetEdRIzFKLLsDrEC3fwuWYyVvrj?usp=drive_link)** – Miscellaneous sources  

Each entry records its source for transparency and traceability.

---
## Lexicon Schema Structure

The lexicon is stored in **CSV** and **JSON** formats. Below is the standardized schema.

### JSON Example

```json
{
  "id": "0001",
  "word": "adda",
  "enclitic_particle": "met",
  "category": "emphasis",
  "snippet_usage": "Adda met dagiti taraken da Pader.",
  "english_translation": "The Pader family also has livestock.",
  "context": "Used to emphasize existence in contrastive statements.",
  "pragmatic_function": "Adds contrast or nuance, similar to 'also' or 'too'.",
  "clitic_position": "Second-position enclitic.",
  "notes": "The particle 'met' can soften a statement or indicate contrast.",
  "source_url": "https://arielsotelotabag.blogspot.com/2008/09/littugaw.html"
}

```

### CSV Example
- **id.** A unique identifier for each entry.
- **word.** The lexical host (word or phrase) to which the enclitic particle attaches.
- **enclitic_particle.** The enclitic particle itself.
- **category.** The pragmatic or functional category of the particle.
  - Categories include:
  - *Class 1: Completion, Addition*
  - *Class 2: Impatience / Command*
  - *Class 3a: Interrogative, Reporting*
  - *Class 3b: Pessimism / Emphasis*
  - *Class 4: Speculation*
  - *Class 5: Affirmation*
  - *Other: Speculation, Hope / Necessity, Discovery*
  
- **snippet_usage.** A sentence or phrase excerpt showing authentic usage.
- **english_translation.** English rendering of the snippet, preserving both literal meaning and pragmatic nuance.
- **context.** The discourse environment or conversational situation of occurence
- **pragmatic_function.** Communication effect that gives deeper meaning to the context
- **clictic_position.**  Placement of a clitic relative to words in the sentence or phrase 
- **notes.** Supplementary remarks
- **source_url.** The online source for transparency and verification


---
## How to use
*Content to be added soon.*

---

## Deliverables

### 1. Electronic Lexicon
- Format: CSV / JSON 
- Contents: Root words, translations, definitions, POS tags, example usage

### 2. Documentation
- Report/Journal format: Tool design, methodology, preliminary findings
- Includes: Use case of the selected language in an NLP-based tool

---

## Contributors

### The Lokal Se7en

- DE TORRES, John Rey I.
- JASMIN, Ramon Emmiel P.
- LACANILAO, Marvin Patrick D.
- RILLERA, Hans C.
- ROXAS, Johan Rickardo A.
- SICCUAN, Sebastian A.
- TANK, Rithik

