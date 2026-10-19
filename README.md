# Hospital-Financial-information
This repository contains the dataset of 13 categories of hospital-related financial documents and the pseudocode of the YIER-VLM model proposed in our manuscript for reproducibility verification.
```text
Hospital-Financial-information/
├── 01 Medical Outpatient Fee Receipt               # Category 1: Medical outpatient fee receipts
│   ├── MOFR_Creased & Curved (20)                  # Medical outpatient fee receipt samples with crease and curve distortions (20 samples)
│   ├── MOFR_OCR(30)                                # Medical outpatient fee receipt samples with OCR annotations (30 samples)
│   └── MOFR_Manual Entry (20)                      # Medical outpatient fee receipt samples for manual entry test (20 samples)
├── 02 Medical Inpatient Fee Receipt                # Category 2: Medical inpatient fee receipts
│   ├── MIFR_Creased & Curved (20)                  # Medical inpatient fee receipt samples with creased and curved distortion (20 samples)
│   ├── MIFR_OCR(30)                                # Medical inpatient fee receipt samples with OCR annotations (30 samples)
│   └── MIFR_Manual Entry (20)                      # Medical inpatient fee receipt samples for manual entry test (20 samples)
├── 03 Medical Insurance Settlement Schedule        # Category 3: Medical insurance settlement schedules
│   ├── MISS_Creased & Curved (20)                  # Medical insurance settlement schedule samples with crease and curve distortions (20 samples)
│   ├── MISS_OCR(30)                                # Medical insurance settlement schedules samples with OCR annotations (30 samples)
│   └── MISS_Manual Entry (20)                      # Medical insurance settlement schedules samples for manual entry test (20 samples)
├── 04 Self-made Receipt                            # Category 4: Self-made receipts
│   ├── SMR_Creased & Curved (20)                   # Self-made receipt samples with creased and curved distortion (20 samples)
│   ├── SMR_OCR(30)                                 # Self-made receipt samples with OCR annotations (30 samples)
│   └── SMR_Manual Entry (20)                       # Self-made receipt samples for manual entry test (20 samples)
├── 05 Paper-based VAT Ordinary Invoice             # Category 5: Paper VAT ordinary invoices
│   ├── VAT-OI_Creased & Curved (20)                # Paper VAT ordinary invoices samples with creased and curved distortion (20 samples)
│   ├── VAT-OI_OCR(30)                              # Paper VAT ordinary invoices samples with OCR annotations (30 samples)
│   └── VAT-OI_Manual Entry (20)                    # Paper VAT ordinary invoices samples for manual entry test (20 samples)
├── 06 Electronic Ordinary VAT Invoice              # Category 6: Electronic VAT ordinary invoices
│   ├── VAT-EOI_Creased & Curved (20)               # Electronic VAT ordinary invoices samples with creased and curved distortion (20 samples)
│   ├── VAT-EOI_OCR(30)                             # Electronic VAT ordinary invoices samples with OCR annotations (30 samples)
│   └── VAT-EOI_Manual Entry (20)                   # Electronic VAT ordinary invoices samples for manual entry test (20 samples)
├── 07 E-Invoice-EI                                 # Category 7: E-Invoice-EI
│   ├── EI_Creased & Curved (20)                    # E-Invoice-EI with creased and curved distortion (20 samples)
│   ├── EI_OCR(30)                                  # E-Invoice-EI samples with OCR annotations (30 samples)
│   └── EI_Manual Entry (20)                        # E-Invoice-EI samples for manual entry test (20 samples)
├── 08 Electronic Special VAT Invoice               # Category 8: Electronic special VAT invoices
│   ├── VAT-ESI_Creased & Curved (20)               # Electronic special VAT invoices with creased and curved distortion (20 samples)
│   ├── VAT-ESI_OCR(30)                             # Electronic special VAT invoices samples with OCR annotations (30 samples)
│   └── VAT-ESI_Manual Entry (20)                   # Electronic special VAT invoices samples for manual entry test (20 samples)
├── 09 Supermarket & Catering Receipt               # Category 9: Supermarket and catering receipts
│   ├── SCR_Creased & Curved (20)                   # Supermarket and catering receipts with creased and curved distortion (20 samples)
│   ├── SCR_OCR(30)                                 # Supermarket and catering receipt samples with OCR annotations (30 samples)
│   └── SCR_Manual Entry (20)                       # Supermarket and catering receipt samples for manual entry test (20 samples)
├── 10 Electronic Air Transport Itinerary Receipt.  # Category 10: Electronic air transport itinerary receipts
│   ├── EATIR_Creased & Curved (20)                 # Electronic air transport itinerary receipts with creased and curved distortion (20 samples)
│   ├── EATIR_OCR(30)                               # Electronic air transport itinerary receipts samples with OCR annotations (30 samples)
│   └── EATIR_Manual Entry (20)                     # Electronic air transport itinerary receipts samples for manual entry test (20 samples)
├── 11 Bank Collection Receipt                      # Category 11: Bank collection receipts
│   ├── BCR_Creased & Curved (20)                   # Bank collection receipts with creased and curved distortion (20 samples)
│   ├── BCR_OCR(30)                                 # Bank collection receipts samples with OCR annotations (30 samples)
│   └── BCR_Manual Entry (20)                       # Bank collection receipts samples for manual entry test (20 samples)
├── 12 Bank Payment Receipt                         # Category 12: Bank payment receipts
│   ├── BPR_Creased & Curved (20)                   # Bank payment receipts with creased and curved distortion (20 samples)
│   ├── BPR_OCR(30)                                 # Bank payment receipts samples with OCR annotations (30 samples)
│   └── BPR_Manual Entry (20)                       # Bank payment receipts samples for manual entry test (20 samples)
├── 13 Train ticket                                 # Category 13: Train ticket receipts
│   ├── TK_Creased & Curved (20)                    # Train tickets with creased and curved distortion (20 samples)
│   ├── TK_OCR(30)                                  # Train ticket samples with OCR annotations (30 samples)
│   └── TK_Manual Entry (20)                        # Train ticket samples for manual entry test (20 samples)
└── YIER-VLM_pseudocode_simple.pdf                  # Pseudocode of the proposed YIER-VLM model
```

## Dataset Description
This dataset consists of **13 categories of hospital-related financial documents** used in our study for visual document understanding and information extraction tasks. All sensitive personal information in the documents has been fully anonymized to protect privacy.

