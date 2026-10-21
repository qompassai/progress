# Model roster

Capability-themed names for the local models in active use, ratified
2026-10-20. The LLMs run in the rose store on primo and answer to their
roster name as a rose alias tag; the original `hf-*` tags are untouched
and remain the canonical source each alias points at. The media models
are called by file or pipeline, as noted per row.

| Name | Model | Capability | Runs on | How to call |
| --- | --- | --- | --- | --- |
| Ada | Qwen3-Coder 30B (`hf-qwen3-coder-30b`) | Code workhorse: tools + completion | rose, primo (A6000) | rose tag `ada` (`/api/chat`, model `ada`) |
| Aria | ACE-Step 1.5 | Music generation | primo, HF cache | Registry name only: HF cache `models--ACE-Step--Ace-Step1.5`; no alias mechanism |
| Electra | Nemotron 3.5 Lightning 30B (`hf-nemotron-3.5-lightning-30b`) | Fastest generation (142 tok/s measured); tools + thinking | rose, primo (A6000) | rose tag `electra` (`/api/chat`, model `electra`) |
| Frida | Illustrious XL v1.1 | Anime image generation | primo, ComfyUI (A6000) | Checkpoint `~/models/strobe-gen/Frida.safetensors` (symlink to `Illustrious-XL-v1.1.safetensors`) |
| Grace | Devstral 24B tools build (`hf-devstral-24b-tools`) | Agentic coder: tools + completion | rose, primo (A6000) | rose tag `grace` (`/api/chat`, model `grace`) |
| Greta | LTX-Video (Lightricks) | Image-to-video | primo, HF cache | Registry name only: HF cache `models--Lightricks--LTX-Video`; no alias mechanism |
| Iris | Muse Glimmer 30B, vision build (`hf-glimmer-30b-vision`) | Multimodal: vision + tools + chat | rose, primo (A6000) | rose tag `iris` (`/api/chat`, model `iris`) |
| Nina | Phi-4 tools build (`hf-phi-4-tools`) | Small, precise tool-caller | rose, primo (A6000) | rose tag `nina` (`/api/chat`, model `nina`) |
| Vera | Qwen3.6 27B (`hf-qwen36-27b`) | Structured-output generalist: tools + thinking + completion | rose, primo (A6000) | rose tag `vera` (`/api/chat`, model `vera`) |

Bench: the granite tools build (`hf-granite-4.2-8b-tools`) and the
gpt-oss tools build (`hf-gpt-oss-20b-tools`) remain bench tags without
roster names until they earn roster spots in a battery.
