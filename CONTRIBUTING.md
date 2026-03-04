# Contribution Guidelines

Welcome to contribute to the TRAE Community Templates repository! We appreciate your help in making this resource better for everyone.

![TRAE Templates Banner](./assets/image/Templates.gif)

[English](./CONTRIBUTING.md) | [中文](./CONTRIBUTING.zh-CN.md)

## 📋 What You Can Contribute

We welcome various types of contributions:

1. **New Project Templates** - Starters for popular frameworks or technologies
2. **Configuration Files** - Useful config templates (e.g., `.gitignore`, `.editorconfig`)
3. **Documentation Improvements** - Better explanations, examples, or translations
4. **Bug Fixes** - Corrections to existing templates
5. **Feature Requests** - Suggestions for new template categories

## 🚀 How to Contribute a New Template

### Step 1: Fork and Create Branch

```bash
# Fork the repository
git clone https://github.com/trae-community/templates.git

# Create a new branch
git checkout -b feature/your-template-name
```

### Step 2: Create Your Template

#### Choose the Right Category
Place your template in the appropriate directory:
- `templates/web-frontend/` - Web frontend projects
- `templates/backend-service/` - Backend/API services
- `templates/mobile-desktop/` - Mobile or desktop apps
- `templates/data-ai/` - Data science and AI projects
- `templates/tools-devops/` - DevOps and configuration tools

#### Required Files
Every template must include:

1. **README.md** (Required)
   - Project description
   - Tech stack used
   - Installation/setup instructions
   - Usage examples
   - Any special configuration notes

2. **Core Template Files** (Required)
   - The actual code/configuration files
   - Ensure they're functional and tested

3. **.gitignore** (Recommended)
   - Appropriate ignore files for the technology

4. **README.zh-CN.md** (Optional but encouraged)
   - Chinese translation of your README

### Step 3: Template Quality Checklist

Before submitting, ensure your template:

- ✅ Works out of the box (test it fresh)
- ✅ Follows best practices for the technology
- ✅ Includes clear setup instructions
- ✅ Has meaningful comments in code
- ✅ Uses standard project structure
- ✅ Doesn't include sensitive information (API keys, tokens, etc.)
- ✅ Is minimal but complete (avoid unnecessary complexity)

### Step 4: Update Main README

Add your template to the appropriate category table in `README.md`:

```markdown
| **[Your Template Name](./templates/category/your-template)** | Brief description | Tech Stack |
```

Also update `README.zh-CN.md` with the Chinese version.

### Step 5: Test and Commit

```bash
# Test your template one more time
# Add some usage tests if applicable

# Commit your changes
git add .
git commit -m "feat: add [template-name] template"
```

### Step 6: Submit Pull Request

1. Push to your fork
2. Create a Pull Request
3. Fill in the PR description:
   - What does this template do?
   - Why is it useful?
   - Any special notes for reviewers?

## 📝 Documentation Contributions

For documentation improvements:

1. **Typos/Grammar**: Direct fix with clear commit message
2. **Major Rewrites**: Open an issue first to discuss
3. **Translations**: Create `README.zh-CN.md` or improve existing translations

## 🎯 Template Guidelines

### Good Template Characteristics

1. **Minimal but Complete**
   - Include only essential files
   - Show best practices, not every feature

2. **Well Documented**
   - Explain what each file does
   - Provide setup commands
   - Include usage examples

3. **Easy to Use**
   - Should work with minimal configuration
   - Clear "Getting Started" section
   - No hidden dependencies

4. **Follows Conventions**
   - Standard project structure
   - Common naming patterns
   - Industry best practices

### Example Structure

```
your-template/
├── README.md              # Required: Usage instructions
├── README.zh-CN.md        # Optional: Chinese translation
├── .gitignore            # Recommended: Git ignore rules
├── package.json          # Example: Package config (for Node.js)
├── src/                  # Example: Source code
│   ├── index.js
│   └── utils.js
└── config/               # Example: Configuration files
    └── default.json
```

## 🔍 Review Process

After you submit your PR:

1. **Automated Checks**: Ensure all CI checks pass
2. **Maintainer Review**: A maintainer will review within a few days
3. **Feedback**: You may be asked to make changes
4. **Merge**: Once approved, your template will be merged!

## 💡 Tips for Success

- **Keep it Simple**: Focus on common use cases
- **Test Everything**: Verify all commands work
- **Be Responsive**: Reply to feedback quickly
- **Learn from Others**: Check existing templates for reference

## ❓ Questions?

Feel free to:
- Open an issue for questions
- Join our community discussions
- Ask in the PR comments

## 🙏 Thank You!

Your contributions help developers around the world build better applications faster. Every contribution, big or small, makes a difference!

---

Happy contributing! 🎉
