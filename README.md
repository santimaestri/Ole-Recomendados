Olé Recomendados

Daily Product Recommendations on best Mercadolibre's deals for Olé newspaper

Thanks to scraping techniques, I was able to obtain Mercadolibre Argentina offers and deals, filtered and sorted to what people is interested: great products with great prices.

I realised that they are real discounts: checking the day after, the same URL has a higher price. In some cases, it's possible to find errors, like items under ARS 16,000 with free shipping, what makes a price up to 50% less if you discount the shipping price.

I went through Mercadolibre Offers section, [www.mercadolibre.com.ar ](https://www.mercadolibre.com.ar/ofertas?container_id=MLA779357-1&page={page}), and scraped the 20 of them. Then, I created a dataframe with the important information:
- Image
- Link
- Brand
- Title
- Rating
- Quantity of ratings
- Previous price
- Current price
- % of discount
- Installments
- Shipping

Then, with pandas I turned the strings into integers, so I could sort the articles with the different numeric columns. Offering the most popular of them, almost assures a purchase from the reader. Still, including a chart makes it easier for the user, who can search top deals on its own.

The information to be published in the future should be done like a/b testing, as we need to know the audience interests.

Python, Jupyter Notebook, Pandas, Scraping and HTML, made me enhance the experience of this kind of data analysis, it took it to a whole new level so I can understand it better. Usually I did Excel, but now this is much faster, although it might take some time in the set up, it allows automatation, which in the ends, delivers better results. This opens many opportunities too.

The Offer_daily.ipynb shows how the scraping and filtering was done, generating different files according to the filter. Ma