# Supporting the LAJBI Framework

The LAJBI framework is released under the permissive MIT License, which means you are free to use it and its generated output without any attribution requirement.

However, if you find LAJBI valuable and would like to support the project, a simple attribution is a great way to give back. It helps others discover the framework and contributes to the growth of the community.

Below are several easy, copy-and-paste methods to add a "Powered by LAJBI" badge to your work.

---

### For Markdown (e.g., GitHub READMEs)

This is the recommended method for GitHub projects. It uses a theme-aware badge that will automatically switch between a light and dark version based on the viewer's GitHub theme.

**Instructions:**
1. Make sure the badge files (`powered-by-lajbi-light.svg` and `powered-by-lajbi-dark.svg`) are located in an `assets` folder in your repository's root.
2. Copy and paste the following code into your `README.md` file.

```markdown
<a href="[https://github.com/LAJBY/LAJBI](https://github.com/LAJBY/LAJBI)" target="_blank" rel="noopener noreferrer">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="[https://raw.githubusercontent.com/LAJBY/LAJBI/main/assets/powered-by-lajbi-dark.svg](https://raw.githubusercontent.com/LAJBY/LAJBI/main/assets/powered-by-lajbi-dark.svg)">
    <source media="(prefers-color-scheme: light)" srcset="[https://raw.githubusercontent.com/LAJBY/LAJBI/main/assets/powered-by-lajbi-light.svg](https://raw.githubusercontent.com/LAJBY/LAJBI/main/assets/powered-by-lajbi-light.svg)">
    <img alt="Powered by LAJBI" src="[https://raw.githubusercontent.com/LAJBY/LAJBI/main/assets/powered-by-lajbi-light.svg](https://raw.githubusercontent.com/LAJBY/LAJBI/main/assets/powered-by-lajbi-light.svg)">
  </picture>
</a>
```
For Websites and Web Applications (HTML)
You can embed the SVG code directly into your website's footer or relevant section.

Light Theme Badge
For use on light-colored backgrounds.
```markdown
<a href="[https://github.com/LAJBY/LAJBI](https://github.com/LAJBY/LAJBI)" target="_blank" rel="noopener noreferrer" title="Powered by LAJBI">
  <svg width="160" height="30" viewBox="0 0 160 30" fill="none" xmlns="[http://www.w3.org/2000/svg](http://www.w3.org/2000/svg)">
    <rect width="160" height="30" rx="4" fill="#f0f0f0"/>
    <text x="50%" y="50%" dominant-baseline="middle" text-anchor="middle" font-family="Arial, sans-serif" font-size="12" fill="#333">
      Powered by <tspan font-weight="bold">LAJBI</tspan>
    </text>
  </svg>
</a>
```

Dark Theme Badge
For use on dark-colored backgrounds.

```markdown
<a href="[https://github.com/LAJBY/LAJBI](https://github.com/LAJBY/LAJBI)" target="_blank" rel="noopener noreferrer" title="Powered by LAJBI">
  <svg width="160" height="30" viewBox="0 0 160 30" fill="none" xmlns="[http://www.w3.org/2000/svg](http://www.w3.org/2000/svg)">
    <rect width="160" height="30" rx="4" fill="#333333"/>
    <text x="50%" y="50%" dominant-baseline="middle" text-anchor="middle" font-family="Arial, sans-serif" font-size="12" fill="#f0f0f0">
      Powered by <tspan font-weight="bold">LAJBI</tspan>
    </text>
  </svg>
</a>
```
Thank you for your support!
