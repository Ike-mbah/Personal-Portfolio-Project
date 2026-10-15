# Daniel Ike-mbah - HTML-Only Personal Portfolio

## Project Description

Daniel Ike-mbah's personal portfolio website is built completely with semantic, accessible HTML5. It features professional background details, service pricing structures, technical blog articles, an audio player clip, a comprehensive contact form, and sub-folder navigation without any CSS frameworks, JavaScript, or builders.

## Pages Included

- `index.html`: Homepage featuring hero introduction, overview highlights, and fragment links.
- `about.html`: Personal story, core professional principles (description list), and an audio element.
- `services.html`: Pricing data table outlining freelance packages and rates.
- `blog.html`: Article listings with ordered category lists and semantic timestamps.
- `contact.html`: Fully constrained accessible form with text, email, tel, select, radio, checkbox, and textarea inputs.
- `pages/application.html`: Nested project application form verifying correct parent-folder (`../`) navigation links.

## HTML Features Used

- **Semantic Landmarks & Structure:** `<!DOCTYPE html>`, `<html>`, `<head>`, `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`.
- **Text Formatting:** Paragraphs (`<p>`), strong importance (`<strong>`), emphasis (`<em>`), timestamps (`<time>`).
- **Lists:** Ordered lists (`<ol>`), unordered lists (`<ul>`), and description lists (`<dl>`, `<dt>`, `<dd>`).
- **Links:** Internal, external, relative, email (`mailto:`), and fragment (`#`) links with proper cross-folder relative paths (`../`).
- **Media & Figures:** `<figure>` and `<figcaption>` with `<img>` elements, plus HTML5 `<audio>` element with fallback download links.
- **Data Tables:** Real accessible table (`<table>`, `<caption>`, `<thead>`, `<tbody>`, `<tr>`, `<th>` with scope, `<td>`).
- **Forms:** Complete accessible forms utilizing `<fieldset>`, `<legend>`, `<label>`, `<input>` (types: text, email, tel, radio, checkbox), `<select>`, `<textarea>`, constraints (`required`, `minlength`), and `<button type="submit">`.

## What I Learned

- Mastering strict document hierarchies, semantic landmark roles, and accessible form labeling without relying on visual style frameworks.
- Navigating relative file paths accurately between root-level pages and sub-folder documents (`pages/application.html`).
- Ensuring screen-reader compatibility through native semantic elements, table scopes, and explicit label-input associations.

## Challenges Encountered

- Structuring complex form controls (such as nested fieldsets for radio button groups) to guarantee full accessibility compliance.
- Managing relative paths correctly when linking back from nested child folders to root pages.

## Resources and Media Licences / Attributions

- W3C Nu HTML Checker for standards validation.
- Placeholder image asset: `./images/Profile.jpg` (Public Domain / Unsplash source attribution).
- Audio sample: `./media/intro-speech.m4a` (Open Creative Commons audio snippet).
