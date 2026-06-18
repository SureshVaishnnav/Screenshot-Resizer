# Contributing to Screenshot Resizer

First off, thank you for considering contributing to Screenshot Resizer! It's people like you that make Screenshot Resizer such a great tool.

## Code of Conduct

This project and everyone participating in it is governed by a Code of Conduct. By participating, you are expected to uphold this code.

## How Can I Contribute?

### Reporting Bugs

Before creating bug reports, please check the issue list as you might find out that you don't need to create one. When you are creating a bug report, please include as many details as possible:

**How to report a bug:**

1. Use a clear and descriptive title
2. Describe the exact steps which reproduce the problem
3. Provide specific examples to demonstrate the steps
4. Describe the behavior you observed after following the steps
5. Explain which behavior you expected to see instead and why
6. Include screenshots and animated GIFs if possible
7. Include your browser, OS, and device information

### Suggesting Enhancements

Enhancement suggestions are tracked as GitHub issues. When creating an enhancement suggestion, please include:

* Use a clear and descriptive title
* Provide a step-by-step description of the suggested enhancement
* Provide specific examples to demonstrate the steps
* Describe the current behavior and expected behavior
* Include screenshots and animated GIFs if applicable
* Explain why this enhancement would be useful

### Pull Requests

* Fill in the PR template completely
* Follow the JavaScript/HTML/CSS style guides
* Include appropriate test cases
* Update documentation as needed
* End all files with a newline

## Style Guides

### JavaScript Style Guide

* Use `const` for variables that don't change
* Use `let` for variables that do change
* Avoid `var`
* Use meaningful variable names
* Add comments for complex logic
* Keep functions small and focused
* Use arrow functions when appropriate

```javascript
// Good
const resizeImage = (srcImg, targetW, targetH, mode) => {
  // implementation
};

// Bad
var resizeImage = function(srcImg, targetW, targetH, mode) {
  // implementation
};
```

### HTML Style Guide

* Use semantic HTML
* Keep structure clean and organized
* Use data attributes for JavaScript
* Add aria labels for accessibility
* Properly format nested elements

### CSS Style Guide

* Use CSS variables for colors and common values
* Keep selectors simple and specific
* Group related styles together
* Use meaningful class names (BEM convention)
* Mobile-first responsive design

```css
/* Good */
.size-option {
  display: flex;
  gap: 10px;
  padding: 10px 12px;
}

.size-option.selected {
  border-color: var(--accent);
  background: #FEF6F4;
}

/* Bad */
.sizeOpt { display:flex; }
.sizeOpt.sel { border:1px solid red; }
```

## Development Process

1. Fork the repository
2. Create a new branch: `git checkout -b feature/your-feature-name`
3. Make your changes
4. Test thoroughly in your browser
5. Commit with clear messages: `git commit -m "Add: Clear description of changes"`
6. Push to your fork: `git push origin feature/your-feature-name`
7. Create a Pull Request with a detailed description

## Commit Messages

* Use the present tense ("Add feature" not "Added feature")
* Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
* Limit the first line to 72 characters or less
* Reference issues and pull requests liberally after the first line

## Testing Checklist

Before submitting a PR, please test:

- [ ] Works on desktop (Chrome, Firefox, Safari, Edge)
- [ ] Works on mobile (iOS Safari, Chrome Android)
- [ ] No console errors
- [ ] Images resize correctly
- [ ] All three resize modes (Fit, Fill, Stretch) work
- [ ] Apple App Store sizes work
- [ ] Google Play sizes work
- [ ] Custom sizes work
- [ ] Drag and drop works
- [ ] File upload works
- [ ] Download functionality works
- [ ] UI is responsive

## Feature Requests

Some ideas we're considering:

- [ ] Additional device sizes (Android, newer models)
- [ ] Image optimization/compression
- [ ] Watermark support
- [ ] Batch download as ZIP
- [ ] Undo/Redo functionality
- [ ] Image preview grid improvements
- [ ] Dark mode
- [ ] Multi-language support
- [ ] Export presets
- [ ] History/cache of recent resizes

Feel free to pick any of these or suggest your own!

## Additional Notes

### Issue and Pull Request Labels

* `bug` - Something isn't working
* `enhancement` - New feature or request
* `documentation` - Improvements or additions to documentation
* `good first issue` - Good for newcomers
* `help wanted` - Extra attention is needed
* `question` - Further information is requested

## Recognition

Contributors will be recognized in the README and in release notes.

## Questions?

Don't hesitate to reach out:
- Create an issue with your question
- Start a discussion
- Email: suresh.vaishnnav@gmail.com

Thank you for contributing! 🎉
