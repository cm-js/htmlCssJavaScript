**Before you start:** rename this file to `html12b_SEO_lastname.md`, using your own last name. Watch videos 4–6 and use **Part 2** of `html12_ColorsSeoProtocols_StudyGuide.md` (in this folder) to answer. Put the file in an `html12` folder in your `htmlCssJavaScript` repo. Commit and push when you're done.

**Name:** Cody M

---

# Task 12b — Search Engine Optimization (SEO)

Type your answers on the blank line under each **Answer:**, or fix the code inside the code boxes. Explain in your own words where a question asks why.

## 1. How a search engine works

**a.** Put the three steps a search engine uses in order, and describe each one in one sentence of your own.

| Step | Name | What happens |
|---|---|---|
| 1 | Crawl | Specialised programs follow links across pages to find pages. |
| 2 | Index | The search engine stores all results & their "topics" in a list. |
| 3 | Rank | On search, it sorts matching pages and shows the most relevant |

**b.** You just built a new page, but **no other page links to it**. Why might a search engine have trouble finding it? (Hint: think about how crawlers find pages.)

**Answer:** If no pages link to your page, it will be difficult for a crawler to find.


## 2. Organic vs. paid

**c.** You search for "pizza Medina Ohio." The first two results say **Sponsored**. The next ones do not. Which results are organic and which are paid? Which kind can SEO help with?

**Answer:** Sponsored results are paid, every other one is organic. SEO can help organic results.


**d.** A business owner asks, "Why would I spend time on SEO when I could just pay for ads?" Give one reason SEO is still worth it.

**Answer:** Your results will still show up after you stop paying for an ad spot.


## 3. Fix the head

This is the `<head>` of a bakery's home page. It works, but it is weak for SEO.

```html
<head>
  <meta charset="UTF-8">
  <title>Home</title>
</head>
```

**e.** Rewrite it below. Add a strong `<title>`, a meta description, and the viewport meta tag. Make up a name and town for the bakery.

```html
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Named Bakery - City, STATE</title>
    <meta name="description" content="Pastries, desserts, breads, and more for low prices. Order today!">
</head>
```

**f.** Where does the text in your `<title>` show up? Where does the meta description usually show up?

**Answer:** The title shows in the browser tab, while the meta description typically only appears under the page name in search results.


## 4. Fix the page

**g.** Rewrite this code to be better for SEO and accessibility. Fix the alt text, the link text, and the file name.

```html
<img src="IMG_4471.jpg" alt="picture">
<a href="page3.html">Click here</a> to see our menu.
```

Your fixed version:

```html
<img src="pastry_showcase.jpg" alt="A plate of cupcakes in a glass display.">
Visit our online <a href="menu.html">bakery menu</a>.
```

**h.** A page has three `<h1>` tags: one for the logo, one for the page title, and one for the footer. What is wrong, and how should the headings be set up?

**Answer:** Only one h1 tag should be present on a page. The h1 should be used for the page title, and lower headings (or normal text) should be used for the logo and footer.


## 5. Spot the problem

**i.** Here is a meta description someone wrote:

`content="cheap shoes cheap shoes best cheap shoes buy cheap shoes cheap shoes near me"`

What is this called? What will a search engine do about it? Rewrite it as a good description.

**Answer:** This is key-word stuffing, and may cause search engines to filter your site as a scam site. A better description would be ... descriptive, like `"A variety of cheap shoes for sale at [City], [State]."`


**j.** Name **two** SEO choices that also help people who use screen readers. Explain how each one helps both.

**Answer:** Alt text on pictures (so people know what content is there and so the search engine can tell what content your page has), and descriptive labeling in general.


## 6. Your own site

**k.** Write a `<title>` and a meta description for the `index.html` of your DIY website. Then add them to your real `index.html` and push it.

```html
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<link rel="stylesheet" href="style.css">
<title>Electro Guide - Home</title>
<meta name="description" content="An online guide to all electronic music and more.">
```


## Closing 12b — Vocabulary

| Term | Your definition |
|---|---|
| SEO | Search Engine Optimisation, or how you make your website look better to search engines. |
| Crawler (spider) | A program for search engines to find pages to sort and display as results. |
| Organic results | Any search result that isn't paid to be placed high up. |
| Meta description | A description of a website for crawlers and search result descriptions. |
| Keyword stuffing | Repeating key words in hopes of better indexing for search results. |
| SERP | Search Engine Results Page. What you see when you actually search for something. |