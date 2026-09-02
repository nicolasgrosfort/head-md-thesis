# Master Thesis

Research project conducted by Nicolas Grosfort as part of a Master's degree in Media Design at HEAD - Geneva, under the supervision of Sabrina Calvo.

The project content is published on the website [garden.stokhastik.xyz](https://garden.stokhastik.xyz).

## Obsidian

Obsidian is used to produce the content. Linking notes `[[...]]` do not work with GitHub.

## Quartz

Quartz is used to generate a blog based on Obsidian notes.

### First installation

```bash
cd quartz
npm install
```

### Running the development server

```bash
cd quartz
npx quartz build --serve
```
### Running the production server

```bash
cd quartz
npx quartz build
cd public 
npx serve@latest
```

## Deployment

Run the [Deploy to garden.stokhastik.xyz](.github/workflows/deploy.yml) workflow in the GitHub Actions tab.
