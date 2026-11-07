# Vimolix

**Vimolix** is an interactive chemistry explorer that helps users learn about elements, compounds, drugs, alcohols and biomolecules through chemical properties, molecular identifiers, 2D structures and interactive 3D models.

Developed by **Vidhyalashmi S**, B.Tech CSE (AI & ML).

## Features

- Search compounds by name, PubChem CID, molecular formula or SMILES
- View molecular formula, molecular weight, exact mass, XLogP, TPSA, hydrogen-bond donors/acceptors, rotatable bonds, complexity, charge and heavy-atom count
- View Connectivity SMILES, Isomeric SMILES, InChI and InChIKey
- View a 2D structure image
- Interact with a 3D molecular model: rotate, zoom and toggle rotation
- Chemistry quiz with instant feedback and scoring
- Vimo AI Assistant for beginner-friendly explanations based on the currently loaded compound
- Clean, responsive chemistry-inspired interface

## Technology

- HTML5
- CSS3
- Vanilla JavaScript
- PubChem PUG-REST API
- 3Dmol.js for 3D molecular visualization

## Data source

Chemical data is retrieved live from [PubChem](https://pubchem.ncbi.nlm.nih.gov/) using its PUG-REST API.

PubChem PUG-REST supports compound searches and property retrieval through URL-based requests. Common properties include molecular formula, molecular weight, SMILES, InChI, XLogP, TPSA and hydrogen-bond counts. [1][8]

## Deployment

### GitHub Pages

1. Create a GitHub repository named `vimolix`.
2. Upload `index.html`, `styles.css`, `app.js` and `README.md`.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select `main` and `/ (root)`.
6. Save. Your site will be available at:
   `https://your-github-username.github.io/vimolix/`

### Netlify or Vercel

1. Push the repository to GitHub.
2. Import the repository into Netlify or Vercel.
3. Use the project root as the publish directory.
4. Deploy. No build command is required.

## Important note

This application is intended for educational purposes. Chemical, pharmaceutical and safety-related information should be verified with authoritative scientific, regulatory and medical sources before practical use.
