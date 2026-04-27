# Banking Intent Classification 🏦

Proiect realizat in cadrul Programului de Practica @ ICI Bucuresti, Primavara 2026.

## Descriere
Model de clasificare a intentiilor pentru mesaje scurte de asistenta clienti dintr-o platforma bancara digitala. Fiecare mesaj este clasificat intr-una din 77 de categorii de intentii.

## Rezultate
| Model | Acuratete |
|-------|-----------|
| TF-IDF + Regresie Logistica (baseline) | 88.13% |
| DistilBERT fine-tuned | 90.73% |
| BERT-base-uncased fine-tuned | **91.8%** |

## Tehnologii folosite
- Python, PyTorch
- HuggingFace Transformers
- scikit-learn, Pandas
- NVIDIA RTX 4060

## Fisiere
- `Untitled-1.ipynb` - notebook cu codul complet
- `raport_proiect_ICI.docx` - documentatia proiectului
