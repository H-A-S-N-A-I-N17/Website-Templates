Step 1
Build Navigation Bar
Let's start with creating the first component of our website which is a Navbar.

Note that, we will be adding ids and classes to our elements while writing the HTML code itself but we will use them later in CSS for styling.

Task
In index.html file, do the following below line 3:

Inside the body, add a header tag
Inside the header, add a div tag with a class called "NavBar"
Finally inside the div, add an anchor tag with href="", id="navbar-title" and its clickable text as FASHION STORE

Step 2
Add CSS to Nav Bar
After completing the HTML code for our navbar, we are now able to see a clickable text but if you notice then this text has some default CSS properties like margin and font family. So, first let's reset margin, padding and set a particular font-family of our choice for all the elements throughout the website.

Note
For better understanding of CSS problems, always observe the changes in the web page after adding a style to it instead of blindly following the mentioned steps to add the style.

Task
In style.css file, do the following below line 1:

Set margin and padding to "0" and font family to "Arial, sans-serif" for all the elements we are going to use using the universal selector of CSS
Now, let's give some common style to all the anchor tags we are going to use in our website.

Using type selector for anchor tag, set its:

color to "black"
font-weight to "550"
text-decoration to "none" (It will remove the line under the text so that our text will actually look like a text instead of looking like a link)

Step 3
Stylize Nav Bar
Now, Let's style our navbar so that it actually looks like a navbar instead of just a text.

Task
In style.css file, do the following below line 13:

Set below properties to header element using type selector:
height to "60px"
background-color to "#806BDC"
text-align to "center"
Select the div element with class NavBar using class selector and set its padding-top to "18px".

Select the anchor element with id navbar-title using id selector and set its:

color to "white"
font-size to "25px"

Step 4
Table to list fashion items
Now, We have our Navbar. Let's proceed ahead and list the available fashion items at FASHION STORE.

Task
In index.html, do the following below line 10:

add a main section
inside the main element, add a div element with class="Items"
Now, inside our div element, we will be adding a table with 2 rows and 2 columns.

inside the div element, add a table element with id="item-table"
Now, inside body of our table:

Create the first row of our table with 2 columns. Each column should have an img element with src and alt as mentioned below and class="Item-img".
src="https://cdn.codechef.com/download/Contest+images/ROTEST/tshirt.jpeg" and alt="T-Shirts"
src="https://cdn.codechef.com/download/Contest+images/ROTEST/sunglasses.jpeg" and alt="Sun Glasses"
Now, create the second row of our table with 2 columns. Each column should have an anchor element with href="" class="Item-tag" and it's corresponding text as mentioned below:
T-Shirts
Sun<br>Glasses

Step 5 
Add CSS to items list
We have listed the fashion items available at our store but as of now, the items are not properly aligned so let's style our items now.

Task
In style.css file, do the following below line 28:

Select the div element with class="Items" using class selector and set its padding-top and padding-bottom to 15px
Select the table element with id="item-table" using id selector and set its width to 100% (It will take the complete width of its parent container) and text-align to center
Select the img element with class="Item-img" using class selector and set its height to 64px
Select the anchor element with class="Item-tag" using class selector and set its font-size to 14px
Additionally, you can try adding the below CSS:

.Item-tag:hover{ color: #806BDC; }

It will change the color of our item tag whenever we hover on the tag.

Step 6
Add Shopping banner
Now, Let's add our shopping time banner.

Task
In index.html, do the following below line 59:

Add a div element with class="Shopping-container" (This div will contain our shopping time banner and a table of our upcoming sales)
Let's first add the shopping time banner inside our div.

Here, we want our shopping time banner to be clickable hence we will add our shopping time banner image inside an anchor tag so that the image can be clicked.

Inside our div, add an anchor tag with href=""
Inside the anchor tag, add an image with src="https://cdn.codechef.com/download/Contest+images/ROTEST/shopingtime.jpeg", alt="shopping time" and id="shopping-time-img"
As we will be listing our table of upcoming sales just after the shopping time image in the same div so add 3 br tags after the anchor tag so that we can get some space between our image and the table

Step 7
Style shopping banner
Now, Let's style our shopping container and the shopping time banner.

Task
In style.css, do the following below line 50:

select the div element with class="Shopping-container" using class selector and set its background-color to "lightgrey", text-align to "center" and padding-bottom to "30px" (don't worry, you will understand the use of adding padding-bottom after we list the table of upcoming sales in the container)
select the image with id="shopping-time-img" using id selector and set its margin-top to "30px", width to "90vw" (here vw is viewport width i.e., width of the device we are using so 90vw means our banner will be taking 90% of the width of device) and height to "60vh" (similar to vw, vh is the viewport height)

Step 8
Add table for sale
Alright! Now, let's add our table of upcoming sales.

Task
Table will have 1 header row and 2 body rows each with 4 columns.

In index.html, do the following below line 67:

Add a h2 heading as "OUR UPCOMING SALES" and add a br tag after the heading to give some space before we add our table
Add a table element with class="Sales-table"
Inside table, add thead element with class="Sales-table-head"
Now inside thead, add four header columns each with class="Sales-table" and with data "Festival", "Discount", "Starting Date" and "Ending Date" respectively
Now inside the body of table, add 2 rows each having 4 columns each with class="Sales-table" and with the data mentioned below:
"Christmas", "35% 50%", "20 December", "26 December"
"New Year", "60% 75%", "30 December", "6 January"
Use <s> tag to cross off a text.

Step 9
Style sales table
Now, Let's style our table of upcoming sales.

Task
In style.css, do the following below line 62:

Select the table element with class="Sales-table" using class selector and set its:
width to "90vw"
margin to "auto" (It will horizontally center the element in its container)
border to "1px solid grey"
border-collapse to "collapse"
padding to "12px"
Select the header of table with class="Sales-table-head" using class selector and set its background-color to "#806BDC"
Note that after the table, we have some free space in our shopping container because earlier we've added padding-bottom to "30px" for our container. You can try removing padding-bottom property from shopping container and see the difference for better understanding.

Step 10 
Add store description
Now, Let's add some information about our fashion store after the shopping container to attract the users.

Task
In index.html, do the following after line 146:

Add a div element with class="Information"
Inside div, add a h1 heading as "Fashion Store: The One-stop Fashion Destination" and then add a br tag to add some space after the heading before we proceed with our further content
Now add the paragraph "Stepping out and finding a perfect fashion choice is difficult? Why worry when you have your own Fashion Store at home where you can browse through thousands of choices and you can order clothes according to your liking. Don't worry if you don't like the item after you receive it, you can always consider the option for exchanging your item or even you can return your item and you will get the full amount back. Isn't that amazing? Start searching for your desired clothes and see it yourself. Once you are done with your first shopping, we are very sure that you will continue that in future as well and we will try our best to give you more and more choices so that you can have a variety of clothes to choose from and so you can find one which suits you the best.<br><br>What makes us Great? Well few things are listed below:" and then after the paragraph, add two br tags for further content
Add a h2 heading as "Festival Sales" and add a br tag after the heading
Now add the paragraph "We keep coming with different sales on our Indian Festivals where we offer huge discounts on your favorite clothes. If you want to get the notifications of all our future sales then you can subscribe to us and we will make sure that you will not miss any offer in future so that you can get your favorite cloth at the best possible price." and add a br tag after the paragraph

Step 11
Add remaining elements
Now let's complete remaining HTML part of our website.

Task
In index.html, do the following below line 162:

First Let's list our remaining information:

Add the paragraph "Some of our favorite sales are listed below:"
After the paragraph, create an unordered list with 4 list items as "Independence Day Sale", "Diwali Sale", "Christmas Sale" and "New Year Sale" and after the unordered list, add 2 br tags for further content
Add a h2 heading as "Payment Options" and add a br tag after the heading for further content
Finally add the paragraph "We support a large variety of payment options so that you won't miss a cloth due to unavailability of any payment option. You can use a debit card or your credit card to make the payment. Also, you can directly use your UPI ID to make the payment. We also provide EMI options if you think you can not afford a complete amount at once. Other than that, you can directly make your payment through your bank details and even if you are not sure or you are in doubt then you can choose the Cash option where you can pay the amount in cash to our partner who will be delivering your cloth at your doorstep."
Now, Only footer is left for our website so do add it after the main element with content "&#169; 2012-2023 FashionStore.com"

Step 12
Add remaining CSS
Finally, Let's style our information container and the footer to complete our website.

Task
In style.css, do the following below line 74:

Select the div element with class="Information" using class selector and set its:
width to "92vw"
margin to "20px"
font-size to "11px"
color to "#878787"
list-style-position to "inside" (It will push the bullet points also inside our container)
Select the footer using type selector and set its:
height to "50px"
padding-top to "28px"
background-color to "black"
color to "white"
text-align to "center"