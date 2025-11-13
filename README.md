# Attendee Pages

Welcome to the GitHub Workshop 2025! This folder is where you'll add your personal page.

## 📝 How to Add Your Page

### Step 1: Create Your HTML File

1. Copy `example-template.html` and rename it to `yourname.html` (e.g., `john-doe.html`)
2. Edit the file and customize it with your information:
   - Replace `[Your Name]` with your actual name
   - Add your bio, skills, and what you learned
   - Feel free to get creative!

### Step 2: Update the Main Navigation

1. Open `../index.html` (the main homepage)
2. Find the dropdown menu section (around line 37)
3. Add your link inside the `<ul id="attendeeList">` section:

```html
<li><a href="attendees/yourname.html" class="dropdown-link">Your Name</a></li>
```

### Step 3: Commit and Push

1. Save all your changes
2. In GitHub Desktop:
   - Review your changes
   - Write a commit message like "Add [Your Name]'s page"
   - Commit to main
   - Push to your fork

### Step 4: Create a Pull Request

1. Go to your forked repository on GitHub
2. Click "Pull requests" → "New pull request"
3. Write a clear title: "Add [Your Name]'s attendee page"
4. Submit the pull request!

## ✅ Checklist Before Submitting PR

- [ ] My HTML file is named `yourname.html` (lowercase, use hyphens)
- [ ] I updated the navigation in `index.html`
- [ ] My page includes the navbar from the template
- [ ] The favicon and logo paths are correct (`../logo.jpg`)
- [ ] The stylesheet is linked (`../style.css`)
- [ ] All links work correctly
- [ ] My content is original and appropriate

## 🎨 Tips for Customization

- Keep the navbar and footer structure consistent
- Use the existing CSS classes for styling
- Add emojis to make your page fun! 🎉
- You can add more `step-card` divs to show more about yourself
- Test your page by opening it in a browser before submitting

## 🆘 Need Help?

If you're stuck, check out `example-template.html` or ask a workshop mentor!

---

**Happy coding! 🚀**
