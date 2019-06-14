var cardContainer1= $('#1');
var submit1 = $('#a');

submit1.on("click", appendtoDo);

function appendtoDo() {
  var name = $('#d').val();

  cardContainer1.append(`
    <p class="name-to"><input type = "checkbox" class= "checkbox"></input>${name}</p>
  `);
var checkBox = $(".checkbox")
checkBox.on("click", deletetoDo)
  $('.name').val("");
 }

var cardContainer2= $('#2');
var submit2 = $('#b')

 submit2.on("click", appendtoDoOne);

function appendtoDoOne() {
 var name = $('#e').val();

 cardContainer2.append(`
 <p class="name-to"><input type = "checkbox" class= "checkbox"></input> ${name}</p>
 `);
 var checkBox = $(".checkbox")
 checkBox.on("click", deletetoDo)
$('.name').val("");

 }


var cardContainer3= $('#3');
var submit3 = $('#c');

submit3.on("click", appendtoDoTwo);

function appendtoDoTwo() {
  var name = $('#f').val();

  cardContainer3.append(`
    <p class="name-to"> <input type = "checkbox" class= "checkbox"></input>${name}</p>
  `);
  var checkBox = $(".checkbox")
  checkBox.on("click", deletetoDo)
  $('.name').val("");

}

function deletetoDo() {var toDo= $(".name-to")
toDo.remove()
}
