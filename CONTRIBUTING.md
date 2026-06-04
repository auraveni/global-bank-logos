# Contributing to Bank Logos Collection

Thank you for your interest in contributing to this bank logos collection! We welcome contributions from the community.

## 🎯 How to Contribute

### Adding a New Bank Logo

1. **Fork the Repository**
   - Click the "Fork" button at the top right of this repository
   - Clone your forked repository to your local machine

2. **Prepare the Logo**
   - **Format**: SVG only (Scalable Vector Graphics)
   - **Quality**: High-quality, official bank logo
   - **Optimization**: Optimize the SVG file using tools like [SVGO](https://github.com/svg/svgo)
   - **Size**: Keep file size under 50KB
   - **File Naming**: Use lowercase with hyphens (e.g., `chase-bank.svg`, `hdfc-bank.svg`)

3. **Add the Logo File**
   - For Indian banks: Add to `/assets/bank/indian-bank/`
   - For International banks: Add to `/assets/bank/international-bank/`

4. **Update Documentation**
   - Add the bank information to `README.md` in the appropriate table
   - Include: Bank Name, Country, and logo reference
   - Add the bank card to the appropriate HTML page (`indian-banks.html` or `international-banks.html`)

5. **Create a Pull Request**
   - Commit your changes with a clear message: `Add [Bank Name] logo`
   - Push to your forked repository
   - Create a pull request to the main repository
   - Include a description of what you've added

## 📋 Contribution Guidelines

### Logo Requirements

- ✅ Official bank logos only
- ✅ SVG format (required)
- ✅ Clear and recognizable
- ✅ Properly optimized for web
- ✅ No background (transparent)
- ❌ No copyrighted or trademarked content without proper rights
- ❌ No low-quality or pixelated logos
- ❌ No logos with watermarks

### File Naming Convention

```
bank-name.svg
```

Examples:
- ✅ `hdfc.svg`
- ✅ `chase.svg`
- ✅ `state-bank-india.svg`
- ❌ `HDFC_Bank_Logo.svg`
- ❌ `Chase Bank.svg`

### README Update Format

For **Indian Banks**, add to the appropriate category table:

```markdown
| Bank Name | Country | Logo |
|-----------|---------|------|
| Your Bank Name | India | ![Your Bank](/assets/bank/indian-bank/your-bank.svg) |
```

For **International Banks**, add to the appropriate country section:

```markdown
| Bank Name | Country | Logo |
|-----------|---------|------|
| Your Bank Name | Country Name | ![Your Bank](/assets/bank/international-bank/your-bank.svg) |
```

### HTML Page Update

Add a bank card in the appropriate section:

```html
<div class="bank-card">
  <div class="bank-logo">
    <img src="/assets/bank/[category]/your-bank.svg" alt="Your Bank Logo" />
  </div>
  <div class="bank-name">Your Bank Name</div>
  <div class="bank-country">🇮🇳 Country</div>
  <div class="bank-file">your-bank.svg</div>
</div>
```

## 🐛 Reporting Issues

If you find any issues or have suggestions:

1. Check if the issue already exists
2. Create a new issue with:
   - Clear title
   - Detailed description
   - Steps to reproduce (if applicable)
   - Screenshots (if applicable)

## 💡 Suggestions

We welcome suggestions for:
- New banks to add
- Improved organization
- Better documentation
- Enhanced SEO
- Bug fixes
- Performance improvements

## 📝 Code of Conduct

- Be respectful and constructive
- Follow the contribution guidelines
- Help maintain quality standards
- Be patient with review process

## ✅ Pull Request Checklist

Before submitting your pull request, ensure:

- [ ] Logo is in SVG format
- [ ] File is optimized (under 50KB)
- [ ] File naming follows convention (lowercase-with-hyphens.svg)
- [ ] Logo is placed in the correct folder
- [ ] README.md is updated with bank information
- [ ] Appropriate HTML page is updated
- [ ] All information is accurate
- [ ] Commit message is clear and descriptive

## 🔍 Review Process

1. Maintainers will review your pull request
2. May request changes or improvements
3. Once approved, it will be merged
4. You'll be credited as a contributor!

## 📄 License

By contributing, you agree that your contributions will be licensed under the MIT License.

## 🙏 Thank You!

Your contributions help make this resource better for developers worldwide. Thank you for taking the time to contribute!

---

**Questions?** Feel free to open an issue or reach out to the maintainers.
