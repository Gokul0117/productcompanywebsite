# Web Design for a Software Product Company

## AIM:

To design a static website for a software product company company.

## DESIGN STEPS:

### Step 1:

Requirement collection.

### Step 2:

Creating the layout using HTML and CSS.

### Step 3:

Updating the sample content.

### Step 4:

Choose the appropriate style and color scheme.

### Step 5:

Validate the layout in various browsers.

### Step 6:

Validate the HTML code.

### Step 7:

Publish the website in the given URL.

## Code:
### Home.html
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>EduSoft Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">EduSoft Private Limited</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/building.png" alt="Building" />
          <div class="contenttext">
            At Tally, we believe in the power of technology to make business
            owners efficient, empowered and happier, so they can focus on what
            matters most for their business. We design our products to focus on
            just that to make our products work for you, and not the other way
            around.
            <br />
            Our new product TallyPrime takes this to a new level, making your
            start to automation, or your switch to Tally simpler than ever
            before. You can now discover the product much more easily and make
            the product do more for you, without learning anything new. There is
            greater flexibility as the product adapts to your business and your
            way of working. And the transformed look and feel will only make you
            love the product even more.
            <ul>
              <li>Simple to learn, easier to use</li>
              <li>Insightful , actionable & customizable reports</li>
              <li>Anywhere, anytime and secure access</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2023 EduSoft Private Limited, Developed by Gokul J.
      </div>
    </div>
  </body>
</html>
```
### Product.html
``` html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>EduSoft Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">EduSoft Private Limited</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/tally_gold.png" alt="product image">
                  </div>
                  <div class="itemname">Tally Gold</div>
                  <div class="itemprice">Price: Rs.40,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/tally_silver.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally Silver</div>
                  <div class="itemprice">Price: Rs.10,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/product/office.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Microsoft Office 2016</div>
                  <div class="itemprice">Price: Rs.5,499 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/product/1.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Kaspersky Antivirus</div>
                  <div class="itemprice">Price: Rs.5,750.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/product/2.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Bitdefender Antivirus</div>
                  <div class="itemprice">Price: Rs.2,500.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/product/3.png"  alt="product image">
                  </div>
                  <div class="itemname">Adobe Acrobat Pro</div>
                  <div class="itemprice">Price: Rs.5,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/product/4.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Autocad 2017</div>
                  <div class="itemprice">Price: Rs.7,500.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/product/5.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Turbocad LTE</div>
                  <div class="itemprice">Price: Rs.8,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/product/6.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Paint Pro</div>
                  <div class="itemprice">Price: Rs.3,500.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/product/7.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Mcafee Antivirus</div>
                  <div class="itemprice">Price: Rs.4,200.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/product/8.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Norton Antivirus</div>
                  <div class="itemprice">Price: Rs.4,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/product/9.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Quartus Prime</div>
                  <div class="itemprice">Price: Rs.5,500.00 </div>
              </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2023 EduSoft Private Limited, Developed by Gokul J.
      </div>
    </div>
  </body>
</html>
```
### People.html
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>EduSoft Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">EduSoft Private Limited</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitemselected">
          <a href="/static/people.html">People</a>
        </div>
        
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our PEOPLES</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./people/7.jpg" alt="product image">
                  </div>
                  <div class="itemname">Gokul J</div>
                  <div class="itemprice">Founder</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./people/3.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Akaash Raj</div>
                  <div class="itemprice">Post:CEO</div>
              </div>
             
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./people/6.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Pradeep</div>
                  <div class="itemprice">Post:research director</div>
              </div>
            
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./people/4.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Sivaram</div>
                  <div class="itemprice">Post: Product designer</div>
              </div> 

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./people/5.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Sakthivel</div>
                  <div class="itemprice">Post: manufacturing specialist </div>
              </div>

               <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./people/2.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Jayamani</div>
                  <div class="itemprice">Post: Coordinator</div>
              </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2023 TCS Private Limited, Developed by Gokul J.
      </div>
    </div>
  </body>
</html>
```
### Contact.html
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>EduSoft Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">EduSoft Private Limited</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected">
          <a href="/static/contact.html">Contact us</a>
        </div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>TO CONTACT US</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/contact/3.png" alt="product image">
                  </div>
                  <div class="itemname">Call us: </div>
                  <div class="itemprice">6381366409</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/contact/1.png"  alt="product image">
                  </div>
                  <div class="itemname">Mail us:</div>
                  <div class="itemprice">edusoftpvt@gmail.com</div>
              </div>
             
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/contact/2.png"  alt="product image">
                  </div>
                  <div class="itemname">Reach us:</div>
                  <div class="itemprice">Block-87,Gandhi nagar,Chennai-81,Tamilnadu,India.</div>
              </div>
             

         </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2023 TCS Private Limited, Developed by Gokul J.
      </div>
    </div>
  </body>
</html>
```

## OUTPUT:
![Screenshot 2023-06-05 140839](https://github.com/Gokul0117/productcompanywebsite/assets/121165938/6d4a9696-7844-4a9a-ab79-279126bd0fd2)

![Screenshot 2023-06-05 140913](https://github.com/Gokul0117/productcompanywebsite/assets/121165938/e6185fe5-df86-4a72-8e59-922db744394e)

![Screenshot 2023-06-05 140944](https://github.com/Gokul0117/productcompanywebsite/assets/121165938/0ae516e2-c7b8-421d-9e56-19a0cf0d7192)

![Screenshot 2023-06-05 141018](https://github.com/Gokul0117/productcompanywebsite/assets/121165938/c0160637-e91b-4d78-b9d8-9d7fc6c91e29)




## Result:
The program for designing company website for sale of products using HTML and CSS is completed successfully.
