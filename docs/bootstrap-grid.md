# Bootstrap Grid. 

Every page has some sort of layout. 
Layout very simply means how we place the content on the website. 
For example 
Layout with 3 columns on a page. 
Layout with 1 column on the page. 

Bootstrap helps us to create these layouts. 

There are three main components of Bootstrap Grid. 
- Container
- Row
- columns. 

## Container. 
Container basically defines how much spacing we will have horizontally. 
Which in more simpler terms mean how much space we would have at the right and left of the content. 

How to create a container. 
```html
<div class="container">
<!-- Content inside container will come here -->
</div>
```

Container has two classes that we can use. 

1. **container** - Which adds responsive padding to the right and left of content. 
2. **container-fluid** - If the content iside needs to be displayed in full width. 


## Row. 
When ever we want columns we will first add a Row class. 
Row should come insde the containenr as shown below. 
```html
<div class="container">
  <div class="row">
  </div>
 </div>
<!-- Row -->
</div>
```

## Columns. 
Space is divided into 12 portions for columns and is applied using column classes. 

If we want 2 columns of equal sizes. The considering that the we have total 12 portions. It will be 
divided accordingly. So the first portion will be of 6 and second portion would be of 6. 

Example is as follows. 
```html
<div class="container">
  <div class="row">
    <div class="col-6">
    </div>
    <div class="col-6">
    </div>
  </div>
 </div>
<!-- Row -->
</div>
```

If we want a first column to be two portions and the thrird column to be of one portion. 
```html
<div class="container">
  <div class="row">
    <div class="col-8">
    </div>
    <div class="col-4">
    </div>
  </div>
 </div>
<!-- Row -->
</div>
```

