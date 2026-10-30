# Nutori — Your personal ingredient scanner

Snap a photo of any product label and Nutori reads the ingredients, flags allergens,
and explains what's inside — tuned to you, not to a generic score.

[App Store](LINK) https://apps.apple.com/us/app/nutori-labels-that-know-you/id6804901802

## Screenshots
<img width="460" height="997" alt="image" src="https://github.com/user-attachments/assets/4ef70d37-5864-4e4e-a582-a25940aecdf1" />
<img width="460" height="997" alt="image" src="https://github.com/user-attachments/assets/1097e566-7c1a-4dad-bfad-5c61031a1938" />
<img width="460" height="997" alt="image" src="https://github.com/user-attachments/assets/4c7a5f36-f8cf-4c16-9143-102bd17c5a15" />

## Features
- Photo-based ingredient analysis (OCR) with allergen detection
- Nutrition figures calculated against official reference values (MFDS / FDA)
- Shopping mode — scan several products in a row and compare them
- English & Korean UI

## Built with
iOS (Swift / SwiftUI) · Go backend · PostgreSQL · Claude Vision

Solo-built end to end: product design, iOS client, backend, and App Store release (2026).
Backend shared across apps, with a deterministic grounding layer around LLM outputs.
