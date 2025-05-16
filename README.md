# Puzzle Website for aiqplmaj.com

This is a static website containing mathematical puzzles and Latin words that form a puzzle. The site features:

- Three algebraic equations to solve
- A list of Latin words with specific words at positions 4, 17, and 26
- A hint in the footer suggesting the use of a Caesar cipher

## Deployment Instructions

### GitHub Pages

1. Create a new repository on GitHub
2. Upload these files to the repository
3. Go to repository settings and enable GitHub Pages
4. Choose the main branch as the source
5. (Optional) Configure a custom domain in the GitHub Pages settings

### Custom Domain Setup

If you've purchased the domain aiqplmaj.com, you can connect it to your GitHub Pages site:

1. In your GitHub repository, go to Settings > Pages
2. Under "Custom domain", enter your domain name and save
3. Configure your domain with your registrar by adding these DNS records:

```
A     @     185.199.108.153
A     @     185.199.109.153
A     @     185.199.110.153
A     @     185.199.111.153
CNAME www   your-username.github.io.
```

4. Check "Enforce HTTPS" in GitHub Pages settings once DNS is verified

It may take up to 24-48 hours for DNS changes to fully propagate.