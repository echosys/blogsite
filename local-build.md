---
description: How to build and run the Jekyll site locally
---

To run this Jekyll site on your local machine, follow these steps:

### Prerequisites
- **Ruby**: Install Ruby from [rubyinstaller.org](https://rubyinstaller.org/) (use the version with DevKit).
- **Bundler**: Once Ruby is installed, run `gem install bundler` in your terminal.

### Steps to Build and Serve

1. **Install Dependencies**
   Run this command in the root of the repository to install all gems listed in the `Gemfile`:
   ```powershell
   bundle install
   ```

2. **Serve the Site**
   Run the Jekyll development server. The `--livereload` flag will automatically refresh the browser when you make changes:
   ```powershell
   bundle exec jekyll serve --livereload
   ```

3. **Access the Blog**
   Open your browser and navigate to:
   [http://localhost:4000](http://localhost:4000)

4. **Access the Admin Interface**
   If you want to use the local Jekyll Admin UI:
   [http://localhost:4000/admin](http://localhost:4000/admin)

### Troubleshooting
- If you see an error about `webrick`, it is already included in your `Gemfile`.
- On Windows, if you encounter encoding errors, run:
  ```powershell
  chcp 65001
  ```
