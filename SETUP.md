# GitHub par upload kaise karein

## A. Profile README (sabse important)
1. GitHub par naya repo banao, naam EXACTLY: `shivkumaarr` (Public, "Add a README" tick mat karo)
2. `shivkumaarr/README.md` ka content us repo me daal do (ya git push karo)
3. Profile page par README dikhne lagega

## B. Portfolio repo
1. Naya public repo: `security-portfolio`
2. `security-portfolio/` folder ki saari files upload karo
3. Repo Settings → About me description + topics add karo: `penetration-testing`, `vapt`, `cybersecurity`, `mitre-attack`

## C. Git commands
```bash
cd security-portfolio
git init && git add . && git commit -m "Initial commit: security portfolio"
git branch -M main
git remote add origin https://github.com/shivkumaarr/security-portfolio.git
git push -u origin main
```

## D. Profile polish
- Profile photo + bio: "Entry-Level Pentester | VAPT | Red & Blue Team"
- Repos ko Pin karo (security-portfolio + best 3-4)
- Screenshots `assets/` me daalo aur project files me link karo
