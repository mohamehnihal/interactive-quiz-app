# interactive-quiz-app
<!DOCTYPEhtml>
<htmllang=”en”>

<head>
<metacharset=”UTF-8”/>
<metaname=”viewport”
content=”width=device-width, initial-scale=1.0”/>
<title>QuizApp</title>
<linkrel=”stylesheet”href=”style.css”/>
</head>
<body>
<divclass=”container”>
<h1>SimpleQuiz</h1>
<divid=”quiz”>
<divid=”question”>Questiontext</div>
<divid=”options”></div>
<buttonid=”nextBtn”>Next</button>
</div>
<divid=”result”class=”hidden”>

<h2>YourScore:<span id=”score”></span></h2>
<button
onclick=”location.reload()”>Restart Quiz</button>
</div>
</div>


<scriptsrc=”script.js”></script>
</body>
</html>
