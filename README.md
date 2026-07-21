# ansible-ai

Uses fedora server

## models to use

-  big model : Qwen3.6-35B-A3B Q6_K (or Q4) (or if too big Qwen3.6-27B Q6_K or Q4_K_M)
- everyday/small model (with bigger context) : Qwen3.5-9B
- good vision model from different providers : gemma4 12B or Mistral Small 3.2 24B
- task (titles, tags) : qwen2.5:0.5b (try also TiTan-Qwen2.5-0.5B which is finetuned just for tags/titles)
fast utility model: Qwen3.5 2B
- huge model : Llama 3.3 70B Instruct - Q4_K_M or qwen2.5:72b-instruct or Qwen3.5-122B-A10B (Q3)

- uncensored big model : Qwen3.6-27B Abliterated or (more uncensored) Dolphin 3.0 Mistral 24B or Dolphin 3.0 R1 Mistral 24B if reasoning needed or Satyr-V0.1-4B