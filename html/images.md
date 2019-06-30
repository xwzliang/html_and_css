# Images

## Adding images
`<img src="images/quokka.jpg" alt="A family of quokka" title="The quokka is an Australian marsupial that is similar in size to the domestic cat." />`

alt: This provides a text description of the image which describes the image if you cannot see it.

title: You can also use the title attribute with the image element to provide additional information about the image. Most browsers will display the content of this attribute in a tootip when the user hovers over the image.

## Height & Width of images (CSS preferred)
`<img src="images/quokka.jpg" alt="A family of quokka" width="600" height="450" />`

Images often take longer to load than the HTML code that makes up the rest of the page. It is, therefore, a good idea to specify the size of the image so that the browser can render the rest of the text on the page while leaving the right amount of space for the image that is still loading.

## Aligning images horizontally and vertically (This is **Old Code**, should use CSS instead)
`<img src="images/quokka.jpg" alt="A family of quokka" width="600" height="450" align="left"/>` <br>
`<img src="images/quokka.jpg" alt="A family of quokka" width="600" height="450" align="right"/>` <br>
`<img src="images/quokka.jpg" alt="A family of quokka" width="600" height="450" align="top"/>` <br>
`<img src="images/quokka.jpg" alt="A family of quokka" width="600" height="450" align="middle"/>` <br>
`<img src="images/quokka.jpg" alt="A family of quokka" width="600" height="450" align="bottom"/>`

## Figure and figure caption (HTML5)
```
<figure>
  <img src="images/otters.jpg" alt="Photograph of two sea otters floating in water"
  <br />
  <figcaption>Sea otters hold hands when they sleep so they don't drift away from each other.</figcaption>
</figure>
```
