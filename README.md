# PaceBowl - ComfyUI Prompt Studio & Flux.1 Latent Calculator

> The modern web studio for ComfyUI Empty Latent resolution calculation and Flux.1 natural language prompting.

---

## 🚀 Key Features

1. **Empty Latent Image Calculator (1MP Buckets)**:
   - Eliminates artifacting and duplicate heads in Flux.1 and SDXL.
   - Pre-configured buttons for 1:1 (1024x1024), 16:9 (1344x768), 9:16 (768x1344), 4:3 (1152x896), 3:4 (896x1152), 21:9 (1536x640), 3:2, and 2:3.
   - 1-Click "Copy W x H" and "Copy Empty Latent JSON" directly for ComfyUI.
2. **Flux.1 Natural Language Studio (T5-XXL Ready)**:
   - Formats coherent natural prose describing lighting, camera lens (35mm/85mm), film stock (Kodak Portra/Fujifilm), and artistic style.
   - Dual-mode switcher for Flux.1 (sentences, no negative) and SDXL (weighted tags, positive + negative).
3. **100% Client-Side & 0 VRAM Overhead**:
   - Runs in the browser without consuming local GPU memory, preventing CUDA Out of Memory (OOM) crashes during rendering.
4. **Full AEO / GEO / SEO Optimized**:
   - `llms.txt`, `sitemap.xml`, `robots.txt`, and Schema.org JSON-LD structured data.

---

## 📦 Deployment (Cloudflare Pages)

```powershell
npx wrangler pages deploy . --project-name comfyui-prompt-studio --branch main
```
