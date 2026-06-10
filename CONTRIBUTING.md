# Contributing to Awesome Cybersecurity Operations Resources

First off, thank you for considering contributing to this repository! 🙏 Your contributions help make this a valuable resource for the entire cybersecurity community.

## 📋 Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How Can I Contribute?](#how-can-i-contribute)
- [Contribution Guidelines](#contribution-guidelines)
- [Pull Request Process](#pull-request-process)
- [Resource Quality Standards](#resource-quality-standards)
- [Reporting Issues](#reporting-issues)
- [Recognition](#recognition)

---

## 💬 Code of Conduct

### Our Pledge

We are committed to providing a welcoming and inspiring community for all contributors. We respect each other and maintain professional, ethical standards.

### Our Standards

Examples of behavior that contributes to creating a positive environment include:

- Using welcoming and inclusive language
- Being respectful of differing opinions and experiences
- Gracefully accepting constructive criticism
- Focusing on what is best for the community
- Showing empathy towards other community members

Examples of unacceptable behavior include:

- Harassment or discrimination of any kind
- Insulting or derogatory comments
- Trolling or personal attacks
- Publishing others' private information
- Unethical or illegal activity promotion

### Enforcement

Instances of abusive, harassing, or otherwise unacceptable behavior may be reported by contacting the repository maintainers. All complaints will be reviewed and investigated.

---

## 🤝 How Can I Contribute?

### 1. **Add New Resources**
Help us grow the collection by suggesting quality resources:
- Free courses and training platforms
- Security tools and frameworks
- Blogs and educational content
- Research papers and whitepapers
- Community projects and initiatives

### 2. **Improve Existing Content**
- Fix broken or outdated links
- Improve resource descriptions
- Add missing information (cost, difficulty level, etc.)
- Update outdated information
- Enhance formatting and clarity

### 3. **Report Issues**
- Found a broken link? Report it!
- Spotted inaccurate information? Let us know
- Have a suggestion for better organization? Share it
- Identify duplicate resources

### 4. **Suggest Improvements**
- New category suggestions
- Better organizational structure
- Improved resource descriptions
- Additional learning paths
- Better formatting or presentation

### 5. **Expand Documentation**
- Create guides and tutorials
- Add real-world examples
- Document best practices
- Share case studies
- Write methodology explanations

---

## 📝 Contribution Guidelines

### Before You Start

1. **Check Existing Content**: Make sure your resource isn't already listed
2. **Verify Quality**: Ensure the resource meets our quality standards (see below)
3. **Test Links**: Confirm all links are working
4. **Review Scope**: Confirm the resource fits our cybersecurity operations focus

### Resource Quality Standards

To maintain the quality of this repository, all contributions must meet these criteria:

#### ✅ Resource Must

- [ ] Be **directly related to cybersecurity operations** (offensive or defensive)
- [ ] Be **actively maintained** and regularly updated
- [ ] Have **working, active links** (no broken URLs)
- [ ] Be **free or clearly state pricing**
- [ ] Provide **genuine value** to the community
- [ ] Be **accessible** to the intended audience
- [ ] Not be **duplicate** content already in the repository
- [ ] **Not promote malware, hacking for illegal purposes, or unethical activities**

#### 📌 Resource Information Must Include

```markdown
**Resource Name**
- **URL**: [Link to resource]
- **Description**: [Clear, concise description of what it offers]
- **Type**: [Tool/Course/Guide/Framework/Blog/etc.]
- **Level**: 🟢 Beginner | 🟡 Intermediate | 🔴 Advanced
- **Cost**: Free / Freemium / Paid
```

#### 🚫 Resources We Cannot Accept

- ❌ Paid services without free alternatives
- ❌ Tools for illegal activities or unethical hacking
- ❌ Spam, self-promotion, or low-quality content
- ❌ Misinformation or misleading content
- ❌ Resources with broken or invalid links
- ❌ Content unrelated to cybersecurity operations
- ❌ Duplicates of existing resources
- ❌ Commercial solicitations

---

## 🔄 Pull Request Process

### Step 1: Fork the Repository

```bash
# Fork the repo on GitHub, then clone your fork
git clone https://github.com/YOUR-USERNAME/Awesome_Cybersec_Resources.git
cd Awesome_Cybersec_Resources
```

### Step 2: Create a Branch

```bash
# Create a descriptive branch name
git checkout -b add/resource-name
# or
git checkout -b fix/broken-link
# or
git checkout -b improve/category-organization
```

### Step 3: Make Your Changes

Follow the formatting guidelines and add your contributions to the appropriate file(s).

**Common locations:**
- New resource → `RESOURCES.md` or relevant category file in `/categories/`
- Bug fix → appropriate file
- Documentation → `README.md` or relevant documentation

### Step 4: Commit Your Changes

```bash
# Use clear, descriptive commit messages
git commit -m "Add: New threat intelligence resources"
git commit -m "Fix: Update broken VirusTotal link"
git commit -m "Improve: Better organization of web security tools"
```

### Step 5: Push to Your Fork

```bash
git push origin add/resource-name
```

### Step 6: Create a Pull Request

1. Go to the repository on GitHub
2. Click "Compare & pull request"
3. Fill out the PR template with:
   - **Title**: Descriptive title of your changes
   - **Description**: What changes you made and why
   - **Checklist**: Verify all requirements below

### Pull Request Checklist

Before submitting, ensure:

- [ ] I have read the `CONTRIBUTING.md` file
- [ ] My changes follow the resource format guidelines
- [ ] I have verified all links are working
- [ ] I have checked for duplicate resources
- [ ] My descriptions are clear and concise
- [ ] The resource meets quality standards
- [ ] I have specified the correct difficulty level
- [ ] I have listed accurate pricing information
- [ ] My commit messages are clear and descriptive
- [ ] I have not added personal promotional content

### What Happens Next

1. **Review**: Maintainers will review your PR
2. **Feedback**: We may request changes or clarifications
3. **Testing**: We'll verify all links and content
4. **Approval**: Once approved, your PR will be merged
5. **Recognition**: Your contribution will be acknowledged

---

## 💾 Formatting & Style Guide

### Markdown Formatting

```markdown
## Section Title

**Resource Name**
- **URL**: https://example.com
- **Description**: Clear, helpful description of what this resource provides
- **Type**: Tool/Course/Guide/Framework/Blog/Community
- **Level**: 🟢 Beginner | 🟡 Intermediate | 🔴 Advanced
- **Cost**: Free / Freemium / Paid

Brief additional context or tips about using this resource.
```

### Formatting Rules

- Use **bold** for resource names and field labels
- Use `code` for technical terms or commands
- Keep descriptions concise (1-2 sentences typically)
- Use consistent emoji for difficulty levels: 🟢 🟡 🔴
- Include direct links where possible
- Organize resources logically within categories

### Example

**NMAP NSE Scripts**
- **URL**: https://nmap.org/nsedoc/scripts/
- **Description**: Comprehensive documentation of Nmap Scripting Engine scripts for network reconnaissance and vulnerability scanning
- **Type**: Tool Documentation
- **Level**: 🟡 Intermediate
- **Cost**: Free

---

## 🐛 Reporting Issues

### Found a Problem?

1. **Search existing issues** to avoid duplicates
2. **Click "Issues"** → **"New Issue"**
3. **Provide details**:
   - What is the issue? (broken link, inaccurate info, etc.)
   - Where is it located? (file, section)
   - How can we reproduce it?
   - Screenshots if applicable

### Issue Template

```markdown
**Issue Type**: [Bug / Improvement / Question]

**Description**:
[Clear description of the issue]

**Location**:
[File/Section where issue occurs]

**Steps to Reproduce** (if applicable):
1. [First step]
2. [Second step]
3. [etc.]

**Current Behavior**:
[What currently happens]

**Expected Behavior**:
[What should happen instead]

**Screenshots**:
[If applicable]
```

---

## 🎉 Recognition

### How We Credit Contributors

- **Pull Request Comments**: Thank you in merge comments
- **Contributors Page** (coming soon): List of all contributors
- **Monthly Recognition**: Feature top contributors
- **README Updates**: Major contributors acknowledged in README

### Levels of Contribution

- 🟢 **New Contributors**: 1-2 contributions
- 🟡 **Regular Contributors**: 3-10 contributions
- 🔴 **Core Contributors**: 10+ contributions or significant work

---

## 📞 Getting Help

### Questions?

- **General questions**: Open a GitHub Discussion
- **Specific help**: Open an Issue with your question
- **Technical issues**: Email maintainers or open an Issue

### Resources for Contributors

- [GitHub Help Documentation](https://docs.github.com/)
- [How to Write Good Commit Messages](https://chris.beams.io/posts/git-commit/)
- [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

---

## 🚀 Making Your First Contribution

### For First-Time Contributors

1. **Start small**: Fix a typo or add one resource
2. **Read existing PRs**: See how others contributed
3. **Ask questions**: Don't be shy, we're here to help
4. **Check issues**: Look for "good first issue" labels

### Simple First Contribution Ideas

- [ ] Fix a typo or broken link
- [ ] Add one quality resource to your favorite category
- [ ] Improve a resource description
- [ ] Add missing metadata to existing resources
- [ ] Suggest a new category

---

## 📜 License

By contributing, you agree that your contributions will be licensed under the same MIT License as the project.

---

## 🙏 Thank You!

Your contributions make this repository better for everyone. Whether you're adding resources, fixing bugs, or improving documentation, you're helping the cybersecurity community learn and grow.

**Happy contributing!** 🚀

---

**Last Updated**: June 2026  
**Maintained By**: Community Contributors
