# English Vocabulary Flashcards

A mobile-friendly English vocabulary learning web app built with Streamlit. Study ~990 words organized into Korean category tags from Quizlet-style flashcards with Anki-inspired flip cards.

## Features

- Category home screen with rounded widget-style cards
- Flashcard study view with CSS flip animation
- Previous / next navigation
- Random mode to shuffle word order
- Session-based learning status (Learned / Review Again)
- Mobile-first layout for smartphone browsers
- Ready for Streamlit Cloud deployment

## Quick start

```bash
pip install -r requirements.txt
streamlit run app.py
```

Open the local URL in your browser. For the best experience, use a phone or narrow browser window.

## Data

Vocabulary is stored in `vocabulary.json`. Each entry includes:

- `word` — English word
- `category` — Korean category tag from the source list (text inside `[...]`)
- `meaning` — Korean meaning
- `part_of_speech` — part of speech
- `example` — example sentence

The dataset contains **990 words** across **494 categories**.

## Deploy to Streamlit Cloud

1. Push this folder to a GitHub repository.
2. Go to [share.streamlit.io](https://share.streamlit.io).
3. Create a new app pointing to `app.py`.
4. Deploy and open the public URL on your phone.

## Project structure

```
vocabulary_app/
├── app.py
├── vocabulary.json
├── requirements.txt
└── README.md
```
