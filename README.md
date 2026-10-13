# CSI Alumni · React Directory Prototype

**A frontend exploration of an alumni and mentor directory.**

React · CSS · Create React App

[Original demo link](https://balaji91221.github.io/csi-alumini/)

## Purpose

An alumni directory needs to make people, groups, and profile links easy to scan. This project explores that presentation through a page of member cards and navigation for years and cohorts.

## Preview

![Alumni directory preview](https://user-images.githubusercontent.com/101827986/190531548-0f84894d-9716-4bda-a3d8-075a0a2dae85.png)
![Member-card preview](https://user-images.githubusercontent.com/101827986/190531559-a6d97988-fcee-4548-854e-91b8ec8b4ee4.png)

## Included interface

- An alumni-directory heading and navigation layout.
- Year and cohort category links.
- Static member cards with names, role text, images, and profile links.
- Shared styling for the page and card grid.

## Run locally

Open the source directory with Node.js/npm installed:

```bash
npm install
npm start
```

Open [localhost:3000](http://localhost:3000). Use `npm run build` to create a static frontend bundle.

## Component structure

```text
src/index.js → App → Member → directory layout and static cards
```

| File | Responsibility |
|---|---|
| [`src/App.js`](src/App.js) | Root application component |
| [`src/components/Member.jsx`](src/components/Member.jsx) | Directory markup and sample profile content |
| [`src/components/style.css`](src/components/style.css) | Directory presentation |

## Current scope

The categories are navigation links, not implemented data filters. Several linked routes and a referenced navbar image are not included in this repository. Member content is embedded in the component; no directory API, sign-in, or profile-management backend is provided.

The source includes third-party hosted profile assets and sample links. Preserve their attribution and replace sample content with authorized alumni information when adapting the layout. The original demo URL and screenshots are retained as project references.

Bootstrapped with [Create React App](https://github.com/facebook/create-react-app).
