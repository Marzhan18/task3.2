# task3.2
assignment3
<!DOCTYPE html>
<html>
<head>
    <style>
/* Write your code here */
/*CSS*/
.left_part{
  display:inline-flex;
  flex-wrap:wrap;width:500px;
  height:700px;
  background-color:brown;
  font-size:230%;
  color:white;
  padding-left:20px;
}
h1{
  padding-top:160px;
  padding-left:25px;}

ul{
  padding-left:660px;
  position:absolute;
  top:100px;}

.right_part h3{
  display:inline-flex;
  flex-wrap:wrap;
  padding-left:820px;
  position:absolute;
  top:20px;
  font-size:25px;}

.y{
  color:purple;
}
</style>
</head>

/*HTML*/
<body>
<aside class="left_part">
    <h1>Web Technologies</h1>
</aside>
<section class="right_part">
    <h3>Syllabus</h3>
    <div class="">
        <ul>
            <li><a href="#">Week #1</a> Introduction to HTML</li>
            <li><a href="#">Week #2</a> CSS Basics</li>
            <li><a href="#">Week #3</a> CSS Box model</li>
            <li><a href="#">Week #4</a> Flex box model</li>
        </ul>
    </div>
</section>
</body>
</html>
