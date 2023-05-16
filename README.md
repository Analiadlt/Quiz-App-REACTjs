# QUIZ App using ReactJS (Code with Sloba)

Consiste en el desarrollo de un cuestionario con multiple choice, al finalizar muestra el score alcanzado.
Se trabaja con estados locales en React.

## Inizialitation

- 1- npm create vite@latest Quiz-App-REACTjs -- --template react
- 2- cd Quiz-App-REACTjs
- 3- npm add -D sass
- 4- npm i
- 5- npm run dev

## DB para el cuestionario

Para las preguntas se utiliza una DB almacenada en: `https://mockapi.io/` con el siguiente formato JSON:

[
{
"question": string,
"type": string, // puede contener "FIB" (fill in blank) o "MCQs" (multiple choice), según el tipo de pregunta.
"correctAnswer": string
},
]

### Cuestionario usado de ejemplo, almacenado en: `https://644982a3e7eb3378ca4ba471.mockapi.io/questions`
[
{
"id": 0,
"question": "**\_\_** provide a way to pass data from one component to another. Fill in the blank.",
"type": "FIB",
"correctAnswer": "props"
},
{
"id": 1,
"question": "Which of the following is used in React.js to increase performance?",
"choices": [
"Virtual DOM",
"Original DOM",
"Both A and B",
"None of the above"
],
"type": "MCQs",
"correctAnswer": "Virtual DOM"
},
{
"id": 2,
"question": "What is ReactJS?",
"choices": [
"Server-side framework",
"User Interface framework",
"both a and b",
"None of the above"
],
"type": "MCQs",
"correctAnswer": "User Interface framework"
},
{
"id": 3,
"question": "Identify the one which is used to pass data to components from outside",
"choices": [
"Render with arguments",
"setState",
"PropTypes",
"props"
],
"type": "MCQs",
"correctAnswer": "props"
},
{
"id": 4,
"question": "In which language is React.js written?",
"choices": [
"Python",
"Java",
"C#",
"JavaScript"
],
"type": "MCQs",
"correctAnswer": "JavaScript"
},
{
"id": 5,
"question": "What is Babel?",
"choices": [
"JavaScript interpreter",
"JavaScript transpiler",
"JavaScript compiler",
"None of the above"
],
"type": "MCQs",
"correctAnswer": "JavaScript compiler"
}
]
