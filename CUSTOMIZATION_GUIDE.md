# 🎨 Customization Guide for Your GitHub Profile README

This guide will help you personalize your awesome GitHub profile README template!

## 📝 Quick Start Checklist

- [ ] Replace all placeholder text with your own information
- [ ] Update the username in all dynamic widgets
- [ ] Add your social media links
- [ ] Customize the tech stack badges
- [ ] Add your real projects
- [ ] Update work experience
- [ ] Customize colors and themes

## 🔧 Step-by-Step Customization

### 1. Update Your Name and Header

Find and replace `Daniel Hardej` with your name in the header section.

Customize the typing animation by editing these lines:
```markdown
<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=32&duration=2800&pause=2000&color=A855F7&center=true&vCenter=true&width=940&lines=Software+Developer+%7C+Tech+Enthusiast;Building+Amazing+Things+with+Code;Always+Learning%2C+Always+Growing" alt="Typing SVG" />
```

Change the text after `lines=` to show your titles or taglines (separate with semicolons).

### 2. Personalize "About Me" Section

Update all the bullet points with your own information:
- What you're currently working on
- What you're learning
- Collaboration interests
- Topics you can help with
- Contact information
- Fun facts about you

### 3. Tech Stack & Tools

**Add or remove technologies:**
- Visit [shields.io](https://shields.io/) to create custom badges
- Use this format: `![Name](https://img.shields.io/badge/Name-HexColor?style=for-the-badge&logo=logoname&logoColor=white)`
- Find logo names at [simpleicons.org](https://simpleicons.org/)

**Example badge formats:**
```markdown
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
```

### 4. Update GitHub Stats

Replace `danielhardej` with your GitHub username in ALL of these URLs:

**GitHub Stats Card:**
```markdown
https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true
```

**Top Languages Card:**
```markdown
https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact&langs_count=8&theme=tokyonight
```

**GitHub Streak Stats:**
```markdown
https://github-readme-streak-stats.herokuapp.com/?user=YOUR_USERNAME&theme=tokyonight
```

**Activity Graph:**
```markdown
https://github-readme-activity-graph.vercel.app/graph?username=YOUR_USERNAME&theme=tokyo-night&hide_border=true
```

**GitHub Trophies:**
```markdown
https://github-profile-trophy.vercel.app/?username=YOUR_USERNAME&theme=tokyonight&no-frame=true&no-bg=false&margin-w=4&row=1
```

**Profile Views Counter:**
```markdown
https://komarev.com/ghpvc/?username=YOUR_USERNAME&color=blueviolet&style=for-the-badge
```

### 5. Available Themes

You can change the theme for various widgets. Popular themes include:
- `tokyonight` (current)
- `dracula`
- `radical`
- `merko`
- `gruvbox`
- `dark`
- `nord`
- `onedark`

Just replace `theme=tokyonight` with your preferred theme.

### 6. Featured Projects

Update the projects table with your real projects:

```markdown
| Project | Description | Tech Stack | Links |
|---------|-------------|------------|-------|
| 🚀 **[Your Project](https://github.com/yourusername/project)** | Description of your project | `Tech` `Stack` `Here` | [Demo](url) \| [Code](url) |
```

### 7. Social Links

Update all social media links with your profiles:

```markdown
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOURPROFILE)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/YOURHANDLE)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:your.email@example.com)
```

### 8. Work Experience

Replace the placeholder work experience with your actual experience:

```markdown
**Your Job Title** @ [Company Name](https://company.com)  
*Start Date - End Date*
- 🎯 Your achievement
- 🚀 Your contribution
- 👥 Your responsibility
```

### 9. Education & Certifications

Add your real education and certifications:

```markdown
- 🎓 **Your Degree** - University Name (Year)
- 📜 **Certification Name** - Issuing Organization
```

### 10. Dynamic Content (Optional Advanced Features)

**Auto-update Blog Posts:**

To automatically update your blog posts, you can use GitHub Actions with the [blog-post-workflow](https://github.com/gautamkrishnar/blog-post-workflow):

1. Create `.github/workflows/blog-post-workflow.yml`
2. The action will update the section between `<!-- BLOG-POST-LIST:START -->` and `<!-- BLOG-POST-LIST:END -->`

**Auto-update Recent Activity:**

Use the [github-activity-readme](https://github.com/jamesgeorge007/github-activity-readme) action to automatically update your recent GitHub activity.

### 11. Customize Colors

The current theme uses purple/violet colors. To change colors:

**Header typing animation color:**
- Change `color=A855F7` to your hex color (without #)

**Profile view counter color:**
- Change `color=blueviolet` to: `brightgreen`, `green`, `yellow`, `orange`, `red`, `blue`, `grey`, `lightgrey`, or any hex color

**Badge colors:**
- Change the hex code in badge URLs, e.g., `3776AB` in Python badge

### 12. Optional Sections to Remove

If you don't need certain sections, simply delete them:
- Work Experience section
- Certifications & Education
- Blog Posts section
- Goals section
- When I'm Not Coding section

## 🎨 Additional Customization Ideas

### Add More Sections

**Coding Stats (WakaTime):**
```markdown
![WakaTime Stats](https://github-readme-stats.vercel.app/api/wakatime?username=YOUR_WAKATIME_USERNAME&theme=tokyonight)
```

**Spotify Now Playing:**
```markdown
[![Spotify](https://novatorem-YOUR_VERCEL_DEPLOY.vercel.app/api/spotify)](https://open.spotify.com/user/YOUR_SPOTIFY_ID)
```

**Jokes Card:**
```markdown
![Jokes Card](https://readme-jokes.vercel.app/api?theme=tokyonight)
```

**Snake Animation (Contribution Graph):**
Use [snk](https://github.com/Platane/snk) to create an animated snake eating your contributions.

## 🚀 Testing Your Changes

1. Commit and push your changes to GitHub
2. Visit your profile at `https://github.com/YOUR_USERNAME`
3. Your README.md should display automatically
4. Check if all images load correctly
5. Verify all links work

## 📚 Resources

- [Shields.io](https://shields.io/) - Create custom badges
- [Simple Icons](https://simpleicons.org/) - Find brand icons
- [GitHub Readme Stats](https://github.com/anuraghazra/github-readme-stats) - Stats cards
- [GitHub Readme Streak Stats](https://github.com/DenverCoder1/github-readme-streak-stats) - Streak stats
- [Awesome GitHub Profile README](https://github.com/abhisheknaiidu/awesome-github-profile-readme) - More examples

## 💡 Tips

1. **Keep it updated:** Regularly update your README with new projects and achievements
2. **Don't overdo it:** Balance between impressive and readable
3. **Mobile-friendly:** Test how your README looks on mobile
4. **Performance:** Too many large images can slow loading
5. **Accessibility:** Use alt text for images
6. **Be authentic:** Let your personality shine through

## 🤝 Need Help?

If you encounter issues:
1. Check that all URLs use your correct GitHub username
2. Verify image URLs are working (paste in browser)
3. Look at other GitHub profile READMEs for inspiration
4. Open an issue in this repository for support

---

**Happy customizing! 🎉**
