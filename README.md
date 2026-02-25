# LLMachete.com Splash Page

**Purpose**: Minimal, spartan landing page for llmachete.com

**Design**: Clean, centered layout featuring:
- LLMachete logo (inline SVG angular blade symbol)
- Wordmark in brand Deep Teal (#0E5A61)
- Tagline: "Cutting through AI complexity for regulated industries"
- Single CTA link to stories.llmachete.com

---

## Brand Compliance

✅ **Colors**:
- Deep Teal Blue: #0E5A61 (wordmark, primary button)
- Warm Orange: #D97D42 (logo blade symbol)
- Medium Teal: #197A83 (hover state)
- Soft Sand Beige: #F0E7E0 (subtle background)

✅ **Typography**:
- System fonts (clean, web-safe)
- Font weights and spacing match brand guidelines

✅ **Voice**:
- Tagline directly from brand bible
- Minimal, professional tone

---

## Deployment Options

### **Option A: Cloudflare Pages (Recommended)**

1. Create new Cloudflare Pages project
2. Connect to GitHub or Direct Upload
3. Upload `index.html` file
4. Configure custom domain: `llmachete.com`
5. DNS: Point llmachete.com A record to Cloudflare Pages

### **Option B: GitHub Pages**

1. Create repository: `llmachete/llmachete.github.io`
2. Push `index.html` to main branch
3. Enable GitHub Pages in settings
4. Configure custom domain: `llmachete.com`
5. DNS: Point llmachete.com CNAME to `llmachete.github.io`

### **Option C: Any Static Host**

Single file deployment - just upload `index.html` to:
- Netlify
- Vercel
- AWS S3 + CloudFront
- Any web hosting

---

## Local Preview

```bash
# Option 1: Python
cd /home/llmachete/projects/claude-code/LLMachete/content/llmachete-splash-page
python3 -m http.server 8080
# Visit: http://localhost:8080

# Option 2: Direct file
# Just open index.html in browser
```

---

## File Structure

```
llmachete-splash-page/
├── index.html          # Complete splash page (standalone)
└── README.md          # This file
```

---

## Features

- **Responsive**: Works on mobile, tablet, desktop
- **Fast**: Single HTML file, no external dependencies
- **Accessible**: Semantic HTML, proper ARIA labels
- **SEO**: Meta description, proper title tag
- **Smooth interactions**: Hover states, transitions
- **Brand-compliant**: Official colors, typography, messaging

---

## Next Steps

1. Preview locally to confirm design
2. Replace inline SVG logo with actual logo file if preferred
3. Deploy to llmachete.com via chosen hosting option
4. Test custom domain configuration
5. Monitor analytics (optional: add Cloudflare Analytics script)

---

**Status**: Ready for deployment
**Last Updated**: January 2, 2026
