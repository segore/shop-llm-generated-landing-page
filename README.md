# HABIBI SMOKE — الحبيبي

Statische Landing Page für den Habibi Smoke Shop.

## Live-URL

Nach dem ersten erfolgreichen Deployment erreichbar unter:

**https://segore.github.io/shop-llm-generated-landing-page/**

## Deployment

Die Seite wird automatisch über **GitHub Pages** bereitgestellt. Bei jedem Push auf den `main`-Branch läuft ein GitHub Actions Workflow, der die Seite deployt.

Der Workflow kann auch manuell über den Tab **Actions → Deploy to GitHub Pages → Run workflow** ausgelöst werden.

### Einrichtung (einmalig)

1. Im Repository auf **Settings → Pages** gehen.
2. Unter **Source** die Option **GitHub Actions** auswählen.
3. Pushen — der Workflow startet automatisch.

## Projektstruktur

```
index.html          # Komplette Landing Page (HTML, CSS, JS inline)
.github/workflows/
  deploy.yml        # GitHub Actions Workflow für Pages-Deployment
```
