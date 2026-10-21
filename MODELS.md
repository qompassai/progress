# Model roster

Letter-keyed names for the local models in active use, revised and
ratified 2026-10-20: the first letter of each name encodes the
capability, so the roster stays organized at a glance. The LLMs run in
the rose store on primo and answer to their roster name as a rose alias
tag; the original `hf-*` tags are untouched and remain the canonical
source each alias points at. The media models are called by file or
pipeline, as noted per row.

| Name | Letter | Model | Capability | Runs on | How to call |
| --- | --- | --- | --- | --- | --- |
| Aria | A | ACE-Step 1.5 | Audio: music generation | primo, HF cache | Registry name only: HF cache `models--ACE-Step--Ace-Step1.5`; no alias mechanism |
| Clara | C | Qwen3-Coder 30B (`hf-qwen3-coder-30b`) | Code: code workhorse, tools + completion | rose, primo (A6000) | rose tag `clara` (`/api/chat`, model `clara`) |
| Freya | F | Nemotron 3.5 Lightning 30B (`hf-nemotron-3.5-lightning-30b`) | Fast: fastest generation (142 tok/s measured); tools + thinking | rose, primo (A6000) | rose tag `freya` (`/api/chat`, model `freya`) |
| Iris | I | Illustrious XL v1.1 | Image: anime image generation | primo, ComfyUI (A6000) | Checkpoint `~/models/strobe-gen/Iris.safetensors` (symlink to `Illustrious-XL-v1.1.safetensors`) |
| Mira | M | Muse Glimmer 30B, vision build (`hf-glimmer-30b-vision`) | Multimodal: vision + tools + chat | rose, primo (A6000) | rose tag `mira` (`/api/chat`, model `mira`) |
| Opal | O | Devstral 24B tools build (`hf-devstral-24b-tools`) | Operator: agentic coder, tools + completion | rose, primo (A6000) | rose tag `opal` (`/api/chat`, model `opal`) |
| Sylvia | S | Qwen3.6 27B (`hf-qwen36-27b`) | Structured: structured-output generalist, tools + thinking + completion | rose, primo (A6000) | rose tag `sylvia` (`/api/chat`, model `sylvia`) |
| Tessa | T | Phi-4 tools build (`hf-phi-4-tools`) | Tools: small, precise tool-caller | rose, primo (A6000) | rose tag `tessa` (`/api/chat`, model `tessa`) |
| Vera | V | LTX-Video (Lightricks) | Video: image-to-video | primo, HF cache | Registry name only: HF cache `models--Lightricks--LTX-Video`; no alias mechanism |

Bench: the granite tools build (`hf-granite-4.2-8b-tools`) and the
gpt-oss tools build (`hf-gpt-oss-20b-tools`) remain bench tags without
roster names until they earn roster spots in a battery.
