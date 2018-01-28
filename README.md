The Markdown Resume
===================

### Instructions
```bash
git clone https://github.com/mszep/pandoc_resume
cd pandoc_resume
vim resume.md   # insert your own resume info
make
```

### Running Dockerized
```bash
git clone https://github.com/mszep/pandoc_resume
cd pandoc_resume
vim resume.md   # insert your own resume info
docker-compose up -d
```

### Requirements

 * ConTeXt
 * pandoc

#### Mac OSX
Just install docker for mac (don't use brew) and run it dockerized.

#### Debian
```bash
sudo apt install pandoc context
```

#### Fedora
```bash
sudo dnf install pandoc texlive-collection-context
```

#### Arch
```bash
sudo pacman -S pandoc texlive-core
```