# Using-Attributes-Quiz
<!DOCTYPE html>

<!-- Instructions: Using the provided HTML and CSS, add the correct attributes to the HTML to replicate the same webpage pictured below. -->
<!-- Must look like this link_ http://udacity.github.io/fend/lessons/L3/problem-set/06-using-attributes/to-do-list-solution.jpg -->
<html>
<head>
	<meta charset="utf-8">
	<title>Using Attributes Quiz</title>
	<style>
        body {
            font-family: Arial; 
        }
        to-do-list {
            width: 400px;
            background: #2e3d49;
            padding: 10px 20px;
        }
        #title h1 h2 {
            color: #fff;
        }
        .underline {
            text-decoration: underline;
        } 
        .list {
            list-style-type: circle;
            text-align: left;
            font-size: 16px;
            color: #1fba58;
            line-height: 24px;
        }
        .finished {
            color: #f4442f;
            text-decoration: line-through;
        }
	</style>
</head>
<body>
	<div id= "to-do-list">
		<h1 class= "title">My To-Do List</h1>
		<h2 class="underline title">Chores</h2>
		<ul class="list">
			<li>load the diswasher</li>
			<li>vacuum living room</li>
			<li>take out garbage</li>
			<li class="finished">sweep the garage</li>
		</ul>
		<h2 class="underline title">Homework</h2>
		<ul class="list">
			<li class="finished">brainstorm ideas for Science project</li>
			<li class="finished">finish Calculus 2 problems</li>
			<li>study for Programming midterm :P</li>
            <li>finish Project 0 on Udacity FEND</li>
			<li class="finished">find sources for Biology research paper</li>
			<li>read first two chapters of The Art of War</li>
		</ul>
        <h2 class= "underline title">Party</h2>
        <ul class="list">
            <li class="finished">send out invitations</li>
            <li>reserve party room at restaurant</li>
            <li>order the cake!</li>
        </ul>
	</div>
</body>
</html>
