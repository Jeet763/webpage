# webpage
__________________________________


<!DOCTYPE html>
<html lang="en">

<head>


<body>

<div id="google_translate_element"></div>

<script type="text/javascript">
function googleTranslateElementInit() {
  new google.translate.TranslateElement({pageLanguage: 'en'}, 'google_translate_element');
}
</script>

<script type="text/javascript" src="https://translate.google.com/translate_a/element.js?cb=googleTranslateElementInit"></script>


</body>
















 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <meta http-equiv="X-UA-Compatible" content="ie=edge">
 <title>Grocery Item</title>
 <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css">
 <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
 <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
 <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.0/js/bootstrap.min.js"></script>

</head>


<body>
<style>
div {
  background-color: white;
}

div.first {
  opacity: 0.9;
}
</style>

<center><img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAQMAAADCCAMAAAB6zFdcAAAAY1BMVEX///9RUVGHh4fLy8uYmJi7u7tjY2Pk5ORVVVVYWFj7+/v19fVZWVm+vr7o6OhcXFx0dHRsbGy2trbf3t+bm5tqamp+fn6wsLCNjY1CQkJ3d3epqanu7u7T09PFxMXLysuioqKgKSfeAAACdUlEQVR4nO3aW5OiMBCGYeIBOpwiguh6/v+/ctHRKfdicE1mYO19n7mhakhV+xkbAokiAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAC+RfqnscsZQ/LLPIrHrmcMiXG5/STV2PWMITFxmj0Yu54xlO8//ct2EqZ1b59BVOXOhBAFGRSymoZY2vfPIMslCRmvoB9E0UxmIcMTDRnUkodc0FRkEC2kCBitI4NCFgGjdWSQOVP7j9aRQVhXVJJBLdZ/yaskg6CuqCWDkK6oJYOQrqglg5CuqCaDWoxvV1STQUBX1JNB4f0gUE8GqRXPrqgnA/+uqCiD2li/FbSiDKJK5l7jNGXge6+oKYNU/Lqipgx8u6KqDBLj9VxRVQbdvaJPV9SVgV9X1JWB372irgyixqcrKsugNu71rqgsg2jr0RVVvG980K2gi/mLdgreOz9Kc/v6/oPcjV3291rOfIxdNX5IVu7/5rR9qXYX2mGbi43Xz04rKit2cRyiosE1Ri5/sur/klu5nmYmA5U1pLWRXffpT3G+6jttInmRRulcZDNUZYPZi3xM7yyWnp/D1OQfO7lqMYch6hrSWu6T+9T3ymEiu9vRWd9EmJj7C6fMma87gvvc0Feb3t/MO2rN9HaUxubrK6TI/X/a1kzRZf18n+Rl3+6USu5d4CTbHy9qYCcT3z55Iz2XvZ20t6NFX+t8U5VtryEspW9fxl5scz2Y2aAdnv+mRKw7F8utNb3f79HYan1cr6y+S2OnrMzlFvDZ45SDk27hLE5jBJ3DeTObP5/hx2bT6FwuAAAAAAAAAAAAAAAAAAAAAAAAAAD+d78B8d4XU0l+pPgAAAAASUVORK5CYII=" alt="cart" width="200" height="200"><center/>

<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Sofia">
<style>
body {
  font-family: "sans-serif";
  font-size: 22px;
}
</style>
<center><h2 style="color:DodgerBlue;">Welcome to Shopping Cart!<h2/><center/>

 <div class="container">
  <div class="row">
   <div class="col mx-auto col-md-8 mt-3 text-center">
    <div class="alert text-capitalize feedback">
     
    </div>
    <!-- form -->
    <form id="itemForm" class="my-3">
     <h3 class="text-capitalize mb-4 bg-light">Please add your product details.</h3>
     <span class="rounded-bottom"></span>
     <div class="input-group">
      <input type="text" class="form-control text-capitalize" id="itemInput" placeholder="Enter here...">
      <div class="input-group-append">
       <button class="btn btn-primary btn-bg btn-block" type="submit">Add</button>
      </div>
     </div>
    </form>
    <div class="item-container">
     <!-- end of form  -->
     <div class="item-list my-5">
      <!-- single item -->
 <div class="item my-3">
      <h5 class="item-name text-capitalize"></h5>
  <!--    <div>
       <a href="#" class="complete-item"></a>
       <a href="#" class="edit-item"></a>
       <a href="#" class="delete-item"></a>
      </div>-->
     </div>
      <!-- end of single item -->
     </div>
     <button type="button" class="btn btn-primary btn-bg btn-block", id="clear-list">Remove items</button>
    </div>
   </div>
  </div>
 </div>



<head>
<style>
body {
  background-color: white;
}
</style>
</head>


<h5><style>
    /* Image Designing Propoerties */
    .thumb {
        height: 75px;
        border: 1px solid #000;
        margin: 10px 5px 0 0;
    }
</style><h5/>

<script type="text/javascript">
    /* The uploader form */
    $(function () {
        $(":file").change(function () {
            if (this.files && this.files[0]) {
                var reader = new FileReader();

                reader.onload = imageIsLoaded;
                reader.readAsDataURL(this.files[0]);
            }
        });
    });

    function imageIsLoaded(e) {
        $('#myImg').attr('src', e.target.result);
        $('#yourImage').attr('src', e.target.result);
    };

</script>


<input type='file' />
<h4></br><img id="myImg" src="#" alt="your image" height=200 width=100><h4/>



















<body>




<h5><button id="myBtn",button class="btn btn-primary btn-bg btn-block">Add items</button><h5/>
<p><h5> Your items were added on:<h5/><p/>
<p id="demo"></p>



<body>

<input type="file" id="myFile">


<script>
function myFunction() {
  var x = document.getElementById("myFile");
  x.disabled = true;
}
</script>

</body>




<script>

document.getElementById("myBtn").addEventListener("click", displayDate);

function displayDate() {
  document.getElementById("demo").innerHTML = Date();
}
</script>

</body>

<script>
//add an eventListener to the from
const form = document.querySelector('#itemForm'); // select form
const itemInput = document.querySelector('#itemInput'); // select input box from form
const itemList = document.querySelector('.item-list');
const feedback = document.querySelector('.feedback');
const clearButton = document.querySelector('#clear-list');

let todoItems = [];

const handleItem = function(itemName){

    const items = itemList.querySelectorAll('.item');

    items.forEach(function(item){

        if(item.querySelector('.item-name').textContent === itemName){
            //complete event listener
           item.querySelector('.complete-item').addEventListener('click', function(){
                item.querySelector('.item-name').classList.toggle('completed');
                this.classList.toggle('visibility');
            });
            //edit event listener
            item.querySelector('.edit-item').addEventListener('click', function(){
                itemInput.value = itemName;
                itemList.removeChild(item);

                todoItems = todoItems.filter(function(item){
                    return item !== itemName;
                });
            });
            // delete event listener
            item.querySelector('.delete-item').addEventListener('click', function(){
                debugger;
                itemList.removeChild(item);

                todoItems = todoItems.filter(function(item){
                    return item !== itemName;
                });

                showFeedback('item delete', 'success');
            })
        }
    })
}

const removeItem = function(item){
    console.log(item);
    const removeIndex = (todoItems.indexOf(item));
    console.log(removeIndex);
    todoItems.splice(removeIndex, 1);
}

const getList = function(todoItems){
    itemList.innerHTML = '';

        todoItems.forEach(function(item){
            itemList.insertAdjacentHTML('beforeend', `<div class="item my-3"><h5 class="item-name text-capitalize">${item}</h5><div class="item-icons">       <a href="#" class="complete-item"></a>
       <a href="#" class="edit-item"></a>
       <a href="#" class="delete-item"></a></div></div>` );

            handleItem(item);
        });
}

const getLocalStorage = function(){

    const todoStorage = localStorage.getItem('todoItems');
    if (todoStorage === 'undefined' || todoStorage === null){
        todoItems = [];
    } else {
        todoItems = JSON.parse(todoStorage);
        getList(todoItems);
    }
}

const setLocalStorage = function(todoItems){
    localStorage.setItem('todoItems', JSON.stringify(todoItems));
}

// get local storage from page
getLocalStorage();

//add an item to the List, including to local storage
form.addEventListener('submit', function(e){
    e.preventDefault();
    const itemName = itemInput.value;

    if (itemName.length === 0){
        feedback.innerHTML = '.';
        feedback.classList.add('showItem', 'alert-danger');
        setTimeout(
            function(){
                feedback.classList.remove('showItem');
                }, 3000);
    } else {
        todoItems.push(itemName);
        setLocalStorage(todoItems);
        getList(todoItems);
        //add event listeners to icons;
        //handleItem(itemName);
    }

    itemInput.value = '';

    });

    //clear all items from the list
clearButton.addEventListener('click', function(){
    todoItems = [];
    localStorage.clear();
    getList(todoItems);
})


</script>
</html>





_______________________________________





