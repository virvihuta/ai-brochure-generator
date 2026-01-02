# AI Brochure Generator

An AI-powered brochure generator that analyzes a company’s website, intelligently selects relevant pages, extracts key information, and produces a clean, professional marketing-style brochure using a LLM.

This project transforms raw website content into a structured, human-readable company overview suitable for product research, competitive analysis, sales preparation, and company profiling.

---

## Features

- Intelligent website link discovery and filtering  
- Automated content extraction from relevant pages  
- LLM-powered brochure synthesis  
- Structured, factual, marketing-style output  
- Clean markdown output without noise or code blocks  
- Prompt-engineered for deterministic and high-quality results  

---

## How It Works

1. Input a company name and website URL  
2. Crawl and filter internal links to select meaningful pages  
3. Aggregate content from selected pages  
4. Generate a polished markdown brochure using an LLM  

---

## Usage

Run the notebook and call the main function:

```python
create_brochure(
    company_name="HuggingFace",
    url="https://huggingface.co"
)
```
---

## Example Output
The generated brochure typically includes:
- Company overview
- Products and services
- Technology focus
- Company culture and values
- Careers and opportunities
All content is derived from the company’s own website and synthesized into a coherent narrative.

---

## Limitations

- Output quality depends on website structure and available content
- Not intended for legal or compliance documentation
- Requires a valid OpenAI API key

---

## Future Improvements

- Web interface
- PDF and HTML export
- Multi-language brochure generation
- Section-level customization
- Batch processing
- Citation tracking
