# Publish the research site on GitHub Pages

This package is ready to upload. It has not been published, verified in Search Console, or indexed. The planned address is:

https://mingfeng87.github.io/Fractional-De-Giorgi-Conjecture/

## 1. Upload and enable GitHub Pages

1. Extract this ZIP. Open https://github.com/mingfeng87/Fractional-De-Giorgi-Conjecture and choose **Add file → Upload files** from the repository root.
2. Drag in the entire extracted **docs** folder, keeping its folder structure. Commit to **main**. Do not upload the ZIP itself. Keep existing root files, including README and the original PDFs.
3. Open **Settings → Pages**. Choose **Deploy from a branch**, branch **main**, folder **/docs**, then **Save**.
4. Wait for the Pages deployment to succeed. Open the address above and check both manuscript pages and both PDF links. If an earlier site is already configured, check its files and settings before replacing anything.

The `docs` folder is self-contained: no install, build command, API key, or external script is needed. It includes `.nojekyll`; some drag-and-drop uploads omit hidden files, so check that it appears in `docs` after uploading. If missing, create an empty file named `docs/.nojekyll` in GitHub.

## 2. Verify the site in Google Search Console

1. Open https://search.google.com/search-console and add a **URL-prefix** property using the complete planned address above, including the repository path and trailing slash.
2. Select **HTML tag** verification. Copy the exact tag Google provides.
3. Edit `docs/index.html` in GitHub. Paste that tag inside `<head>`, for example immediately after the description meta tag. Commit, wait for the Pages update, then click **Verify** in Search Console. Keep the tag in place afterward.

No verification tag is included in this package because the account-specific token has not been provided. Do not invent one.

## 3. Submit the sitemap and request indexing

In the verified property's **Sitemaps** section, submit:

https://mingfeng87.github.io/Fractional-De-Giorgi-Conjecture/sitemap.xml

Then use **URL inspection → Test live URL → Request indexing** for the homepage and these two pages:

- https://mingfeng87.github.io/Fractional-De-Giorgi-Conjecture/below-half.html
- https://mingfeng87.github.io/Fractional-De-Giorgi-Conjecture/above-half.html

Google decides whether and when to index pages; submission does not guarantee indexing or ranking. Crawling can take days to weeks. A successful deployment is not proof that Google has indexed the site.

## Keeping the site current

- The PDFs are unchanged copies from commit `662b796a5c8e15a9696d1a9f5f4c6ce683b81793`. Their main statements and printed dates are summarized in the HTML pages.
- When revising a manuscript, update its `docs/papers/` copy and any affected title, date, page count, summary, status, and commit-specific reference. Keep the candid candidate-proof status current.
- The HTML displays no author byline and adds no author metadata. The original PDF bytes and their embedded metadata are preserved.
- If the repository, account, or hosting address changes, update the canonical and Open Graph URLs in all three HTML files and every sitemap URL.
- This package does not replace the existing README. Once Pages is live, a link from the repository README to the site can help readers find it.

## Official instructions

- [GitHub Pages publishing source](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
- [Search Console ownership verification](https://support.google.com/webmasters/answer/9008080)
- [Google recrawl and indexing requests](https://developers.google.com/search/docs/crawling-indexing/ask-google-to-recrawl)
