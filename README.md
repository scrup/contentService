# contentService
# 🚀 Automated Marketing Visual Generator (n8n Workflow)

This project is an automated pipeline built in **n8n** that transforms technical product datasheets (PDFs) into complete marketing assets including:

- LinkedIn posts
- Marketing captions
- AI-generated visual prompts
- Product images (via FLUX.2-dev)
- PDF brochures

The goal is to convert raw technical specifications into **high-impact commercial visuals and content** for B2B marketing.

---

# 🧠 Project Overview

Instead of manually creating marketing materials from product datasheets, this workflow automates the entire process:

### Input:
- PDF datasheets from manufacturers (Samsung, LG, Hikvision, Dahua, Horion, etc.)

### Output:
- Marketing-ready text (benefits-oriented)
- Structured product messaging
- AI image generation prompts
- Visual marketing images
- Downloadable PDF brochures

---

# ⚙️ Tech Stack

| Component | Tool |
|----------|------|
| Workflow Automation | n8n (Docker) |
| Text Extraction | Docling |
| Text & Prompt Generation | Google Gemini |
| Image Generation | black-forest-labs/FLUX.2-dev |
| PDF Brochure Generation | Gotemberg API |

---

# 🔄 Workflow Architecture

## 1. PDF Ingestion
- Upload product datasheet (PDF)
- Trigger n8n workflow

## 2. Text Extraction (Docling)
- Extract raw text from PDF
- Clean and structure specifications

## 3. Feature Engineering (Gemini)
- Convert technical specs into marketing benefits
- Select top 5–8 selling points
- Generate structured marketing content

Example transformation:

| Technical Spec | Marketing Benefit |
|------|------|
| 86" 4K UHD | Ultra-clear large-format display |
| Wi-Fi 6 | Ultra-fast stable connectivity |

---

## 4. AI Visual Prompt Generation (Gemini)
- Generate optimized prompts for image creation
- Adapt prompts for LinkedIn / marketing visuals

---

## 5. Image Generation (FLUX.2-dev)
- Generate high-quality product visuals
- Corporate/B2B advertising style
- Export 1080×1920 or 1200×627 formats

---

## 6. Brochure Generation (Gotemberg)
- Create structured PDF brochure
- Includes:
  - Product image
  - Key features
  - Marketing headlines
  - Professional layout

---

# 🎯 Key Features

- Fully automated B2B marketing content pipeline
- Converts technical PDFs into commercial storytelling
- AI-powered visual generation (FLUX.2-dev)
- Multi-format output (LinkedIn, Facebook, Instagram, brochures)
- Scalable for product catalogs

---

# 📦 Output Examples

Each product generates:

## 📝 Marketing Text
- Pain-point driven LinkedIn post
- Feature-to-benefit translation
- Structured product messaging

## 🎨 AI Image Prompt
- Premium corporate advertising prompts
- Designed for FLUX.2-dev

## 🖼️ Visual Assets
- LinkedIn post images
- Social media creatives
- Product hero visuals

## 📄 PDF Brochure
- Ready-to-send commercial document
- Brand-consistent layout

---

# 🧩 Workflow Summary
