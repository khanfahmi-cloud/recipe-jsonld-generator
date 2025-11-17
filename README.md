# Recipe JSON-LD Generator 🍳

![Food Blogging](https://img.shields.io/badge/Food-Blogging-green)
![SEO](https://img.shields.io/badge/SEO-Optimized-blue)
![JSON-LD](https://img.shields.io/badge/JSON--LD-Ready-orange)
![Google Rich Snippets](https://img.shields.io/badge/Rich-Snippets-success)

> Generate perfect structured data for your recipes to get **rich snippets** in Google search results. Increase your click-through rate by up to 35%!

## 🚀 Quick Start

### Option 1: Use the Web Tool (Recommended)
1. Open **[generator.html](generator.html)** in your browser
2. Fill in your recipe details
3. Copy the generated JSON-LD code
4. Paste into your recipe page's `<head>` section

### Option 2: Use the Template
1. Copy **[recipe-template.json](recipe-template.json)**
2. Customize with your recipe details
3. Add to your website

## 💡 Why This Matters

**Recipe rich snippets** can dramatically improve your Google visibility:

✅ **Recipe Cards** - Show directly in search results  
✅ **Star Ratings** - Display your review scores  
✅ **Cooking Times** - Help users plan their cooking  
✅ **Nutrition Info** - Show calories and dietary info  
✅ **Mobile-Friendly** - Better experience on phones  
✅ **Higher CTR** - Stand out from competing recipes  

## 🛠️ Files Included

| File | Purpose |
|------|---------|
| [`generator.html`](generator.html) | **Interactive web tool** - Easy form-based generator |
| [`recipe-template.json`](recipe-template.json) | **Complete template** - Ready-to-customize JSON-LD |
| `README.md` | **Documentation** - This guide |

## 📚 Implementation Guide

### For WordPress Users:
1. Install a "Header and Footer Scripts" plugin
2. Paste the JSON-LD code in the header section
3. Save and test with [Google's Rich Results Test](https://search.google.com/test/rich-results)

### For Static Sites:
1. Add the JSON-LD code between `<script type="application/ld+json">` and `</script>` tags
2. Place in the `<head>` section of your recipe page

### For CMS Platforms:
- **SquareSpace**: Use code injection in page settings
- **Wix**: Add HTML iframe or use Velo code
- **Shopify**: Edit theme liquid files

## 🍪 Example Output

```json
{
  "@context": "https://schema.org/",
  "@type": "Recipe",
  "name": "Classic Chocolate Chip Cookies",
  "description": "The perfect chewy chocolate chip cookies with crispy edges",
  "prepTime": "PT15M",
  "cookTime": "PT12M",
  "recipeIngredient": [
    "2 cups all-purpose flour",
    "1 cup chocolate chips"
  ]
}
