# Exp-4-Create-a-Web-Layout-using-GridBOX
## AIM:
To ceate a web-layout using gridbox

## SOFTWARE:
Visual Studio Code

## ALGORITHM:
1.Start by creating the basic HTML structure for your web page

2.Create a CSS file (e.g., styles.css) and link it to your HTML file. Then, define the styles for the grid layout using the grid-template-areas, grid-template-columns, and grid-template-rows properties.

3.Feel free to customize the grid layout by adjusting the grid areas, columns, and rows to match your specific design requirements. You can add more elements or modify the existing ones.

4.Open the HTML file in a web browser to see the web layout created using the CSS Grid. You should have a header at the top, a sidebar on the left, content in the center, and a footer at the bottom.

5.Run the program.

## PROGRAM:
```
java
<!doctype html>
<title>Example</title>
<style>
body { 
  display: grid;
  grid-template-areas: 
    "header header header"
    "nav article ads"
    "footer footer footer";
  grid-template-rows: 60px 1fr 60px;
  grid-template-columns: 20% 1fr 15%;
  grid-gap: 10px;
  height: 100vh;
  margin: 0;
  }
header, footer, article, nav, div {
  padding: 20px;
  background: rgb(63, 97, 102);
}
#pageHeader {
  grid-area: header;
}
#pageFooter {
  grid-area: footer;
}
#mainArticle { 
  grid-area: article;      
  }
#mainNav { 
  grid-area: nav; 
  }
#siteAds { 
  grid-area: ads; 
  }
</style>
<body>
  <header id="pageHeader">Header</header>
  <article id="mainArticle">Article</article>
  <nav id="mainNav">Nav</nav>
  <div id="siteAds">Ads</div>
  <footer id="pageFooter">Footer</footer>
</body>
```
## OUTPUT:
![image](https://github.com/sangeethak15-AI/Exp-4-Create-a-Web-Layout-using-GridBOX/assets/93992063/31b15027-cacb-4e54-a63c-4739a3d3f9e0)

## RESULT:
Thus the web-layout using gridbos is created.
