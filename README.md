# Challenge #1: Code Refactor by Chi Chiu Lam

My processes of working on this challenge as follows:

1. Open the HTML link to view the webpage

2. Identify what semantic tags could be used to replace all `div` in order to make the markup easy to read

3. Identify if there are any redundant code in CSS by consolidating classes and elements

4. Read the code to verify and make sure no changes on the webpage  

5. Double check if there are any typos 

6. Push the project on Github

## Code Refactor Examples

1. Replace all `div` using semantic tags

Before

```html
<div class="search-engine-optimization">
            <img src="./assets/images/search-engine-optimization.jpg" class="float-left" />
            <h2>Search Engine Optimization</h2>
            <p>
                The dominance of mobile internet use means that users are searching for the right business as they travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increase your visibility and find the right customers for your business.
            </p>
</div>
```
After

```html
<section class="search-engine-optimization">
            <img src="./assets/images/search-engine-optimization.jpg" class="float-left" />
            <h2>Search Engine Optimization</h2>
            <p>
                The dominance of mobile internet use means that users are searching for the right business as they travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increase your visibility and find the right customers for your business.
            </p>
</section>
```

2. Consolidate some redundant code in CSS

Before
```css
.benefit-lead h3 {
    margin-bottom: 10px;
    text-align: center;
}

.benefit-brand h3 {
    margin-bottom: 10px;
    text-align: center;
}

.benefit-cost h3 {
    margin-bottom: 10px;
    text-align: center;
}
```
After

```css
h3 {
    margin-bottom: 10px;
    text-align: center;
}
```
