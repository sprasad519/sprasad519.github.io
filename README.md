# sprasad519.github.io

Here's a clean and professional Markdown file for your Jekyll installation instructions:

---

# 🚀 Jekyll Installation Guide (Ubuntu)

Follow the steps below to install Jekyll on Ubuntu.

---

## ✅ **Step 1: Install Required Packages**

Run the following commands in the terminal:

```bash
sudo apt-get install -y ruby-full build-essential zlib1g-dev
```

---

## 🔧 **Step 2: Configure RubyGems**

Add the following lines to your `~/.bashrc` file:

```bash
echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc
```

---

## 📦 **Step 3: Install Jekyll and Bundler**

Run the command below to install Jekyll and Bundler:

```bash
gem install jekyll bundler
```

---

## 🎯 **Verification**

To confirm the installation, run:

```bash
jekyll -v
```

You should see the installed version displayed.

---

✅ **You’re all set!** 🎉 You can now start building your Jekyll-powered website. 🚀
