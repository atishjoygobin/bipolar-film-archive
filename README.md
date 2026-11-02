# Bipolar Film Archive

## Feeling good?

Many people cannot spot the signs of a manic episode. Recognising these signs early, whether in yourself or in others, can create the opportunity for early intervention before symptoms escalate. Look for a noticeable, sustained change from someone's usual self, especially several signs together: unusually elevated or irritable mood, much more energy or activity, needing far less sleep, racing thoughts or fast speech, unusually high confidence, increased messaging or posting on social media, delusions of grandeur, or an increase in impulsive or risky decision-making, such as excessive spending or uncharacteristic sexual activity. If you notice these signs in yourself, reach out to a trusted person and let them know what's happening so they can help you recognise if things are getting worse. If you are worried about someone you know, calmly describe what you have noticed and offer to help them reach care. See [NHS guidance (UK)](https://www.nhs.uk/mental-health/conditions/bipolar-disorder/) or [NIMH guidance (US)](https://www.nimh.nih.gov/health/publications/bipolar-disorder).

This repository holds the research data behind the Bipolar Film Archive.

The CSV contains 457 works currently included in the archive, with evidence notes and source links. It includes works without TMDb IDs, so coverage is not limited to TMDb records.

## Data file

- `bipolar_film_archive.csv` - archive records, including work details, relevance, diagnosis terminology, subject, evidence, and source references.

## Relevance labels

- **Central** - Bipolar disorder or lived experience is a main subject or major focus of the work.
- **Substantial** - It is an important part of a character's or participant's story, but not the work's main focus.
- **Incidental** - It appears as a brief or secondary reference, diagnosis, or discussion.

## Credits and data sources

- **TMDb:** This product uses the TMDB API but is not endorsed or certified by TMDB. Film metadata and most poster images are drawn from [The Movie Database](https://www.themoviedb.org/) and its API.
- **MovieWords:** Word counts derived from the [OPUS OpenSubtitles corpus](https://opus.nlpl.eu/) (Lison & Tiedemann, 2016), subtitles by [OpenSubtitles.org](https://www.opensubtitles.org/). The MovieWords dataset is licensed [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).
- **MovieLens:** F. Maxwell Harper and Joseph A. Konstan (2015), ["The MovieLens Datasets: History and Context," ACM Transactions on Interactive Intelligent Systems 5(4)](https://doi.org/10.1145/2827872).