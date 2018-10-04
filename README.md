# epicpxls-js library

The library that allows authors of epicpxls to share their products on other websites easily. www.epicpxls.com

## More details

[EpicPxls embed page](https://www.epicpxls.com/embed)

## For developers

Add the script to your html page. It can be before the `</body>` tag.
```html
<script type="text/javascript" src="https://buy.epicpxls.com/external/epicpxls.js"></script>
```

### Buy now button

You can use the below code to get a generated buy now button in an iframe
```html
<a href="https://www.epicpxls.com/items/[PRODUCT-KEY]/" class="epicpxls-buy-button">Buy our 100+ icons</a>
```

You can also use the below code to get a custom link that you can style.

```html
<a href="https://www.epicpxls.com/items/[PRODUCT-KEY]/" class="epicpxls-buy-button-custom">Buy our 100+ icons</a>
```

### Sample button

You can offer people the button to download the free file you offer them on epicpxls.

```html
<a href="https://www.epicpxls.com/items/[PRODUCT-KEY]/" class="epicpxls-sample-button">Buy our 100+ icons</a>
```

To get the same link but with a custom button style you want to define use the below

```html
<a href="https://www.epicpxls.com/items/[PRODUCT-KEY]/" class="epicpxls-sample-button-custom">Buy our 100+ icons</a>
```

#### Table of classes

| Class  | Description  |
|:---|:---|
| epicpxls-buy-button  | Will result in an iframe that will render a button on your page. This button will open the dialog to buy the item. |
| epicpxls-buy-button-custom  | Can be used on any element that is clickable and you can style it as you wish. The action will be to open the dialog to buy the product |
| epicpxls-sample-button | This will offer your users the button to download the free file you assigned to your item |
| epicpxls-sample-button-custom | This will offer you the same option as the custom buy button and you can use it on any clickable element to allow users to download the free sample file |

## Credits

[EpicCoders](http://epiccoders.co) for [EpicPxls](https://www.epicpxls.com)