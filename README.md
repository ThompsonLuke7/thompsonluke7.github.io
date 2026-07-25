# [thompsonluke7.github.io](https://thompsonluke7.github.io/)

Personal GitHub Pages website.

## Theme Explorer

An interactive 3D map of stock-market themes and their relationships.

### How it works

- **Theme construction:** Ticker embeddings are clustered with UMAP and HDBSCAN, then labeled and related by an LLM.
- **Node size:** Established-theme nodes scale with aggregate primary-member market capitalization. Provisional nodes scale with emerging-theme score.
- **Layout:** A force-directed simulation pulls strongly related themes together and separates weakly related or unlinked themes.
- **Edges:** Edge strength controls the target distance between nodes and represents an LLM-inferred economic relationship.

## Screenshots

<!-- Keep your existing image lines below this comment -->
<img width="553" height="1285" alt="image" src="https://github.com/user-attachments/assets/c65724e1-1b2e-4b24-88ae-b89081451a8d" />

<img width="1347" height="1192" alt="Screenshot 2026-07-24 235412" src="https://github.com/user-attachments/assets/a8f5851c-83ae-4fca-b491-5527857f6e20" />

<img width="3413" height="1261" alt="Screenshot 2026-07-24 235314" src="https://github.com/user-attachments/assets/74138d16-15d1-4450-bfdf-6df81e4374dd" />
