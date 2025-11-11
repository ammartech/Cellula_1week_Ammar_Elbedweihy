
# Cellula 1‑Week Deliverables (Advanced Edition)

## Structure
```
Cellula_1week_AmmarElbedweihy/
├─ LSTM/
│  ├─ lstm_training.ipynb                 (basic)
│  └─ lstm_training_advanced.ipynb        (advanced: early stopping, scheduler, class weights, ROC-AUC, PDF)
├─ BERT family/
│  ├─ distilbert_albert.tex               (basic)
│  ├─ distilbert_albert_advanced.tex      (enhanced 5-page template)
│  ├─ lora_qlora.tex                      (basic)
│  ├─ lora_qlora_advanced.tex             (enhanced 3-page template)
│  └─ Makefile
└─ Bonus/
   ├─ finetune_distilbert_lora.ipynb            (basic)
   ├─ finetune_albert_lora.ipynb                (basic)
   ├─ finetune_distilbert_lora_advanced.ipynb   (LoRA with better targets/metrics)
   ├─ finetune_albert_lora_advanced.ipynb       (LoRA with better targets/metrics)
   └─ finetune_distilbert_qlora_advanced.ipynb  (QLoRA 4-bit + gradient checkpointing)
```

## Notes
- LSTM (advanced) includes packed sequences, gradient clipping, StepLR, early stopping, per-class report, confusion matrix, and PDF export.
- PEFT notebooks save LoRA adapters and produce confusion matrices + metrics JSON.
- LaTeX templates are expanded with structure and evaluation guidance. Use `make` inside the `BERT family` folder to compile.
