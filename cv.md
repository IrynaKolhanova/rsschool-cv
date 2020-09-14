# Iryna Kolhanova

## Contacts
* phone: +38 066 77 823 77
* email: iryna.kolhanova@gmail.com

## Front-End Developer
Self-motivated, competent 'HTML Programmer' seeking a challenging position within IT company to use my programming expertise in delivering visually appealing and interactive web applications within given time constraints.

## Skils
**tech skills:**
* HTML, CSS, JavaScript, Git & GitHub, Java, SQL.
**soft skills:**
* Scrum, Agile, Teamwork, GTD

## Description projects:
1) Developed and designed a dynamic responsive website for leisure living and its subsequent businesses.
2) Using Javascript events to manipulate the elements depending on the user interactions.
3) Working as a Junior Web Developer and participating in coding, testing, debugging new applications and website with the team of designers, developers, and content creators to create digital tools.
4) Developing the UI layout and front-end programming for a web application that matched requirements.
5) Creating a responsive single page web application with a different module like a dashboard, notification, application alert for user interface.

## Work experience 
**Junior QA Tester** Freelance
May 2019 - up to now - Ukraine
* Creating and executing test cases;
* Creating and maintaining Test Plans, Test Cases;
* Review and analyze system specifications;
* Manual testing of web and mobile applications;
* Communication with internal development teams regarding requirements clarifications and quality expectations;
* Running functionality, usability, GUI testing , API - testing, cross-browser testing of web-based applications.

## Education 
V. N. Karazin Kharkiv National University (The School of Sociology)
Master’s degree in management sociology and social work.
Septermber 2009 - June 2014 - Ukraine 

## Certification
2020 - Online courses “The Fundamentals of Web UI development”, “The Fundamentals of Software Testing”, “The basics of Python programming” in Prometheus. 
2019 - Online course “The Fundamentals of Software Testing” in QATestLab Training Center.

## Latest code example
    const newTodo = document.querySelector('new-todo');
    const addTodoBts = document.querySelector('add-todo');
    const todoList = document.querySelector('todo-list');

    addTodoBts.addEventListener('click', addNewTodo);

    todoList.addEventListener('click', (event) => {
    const target = event.target;
    if (target.classList.contains('todo-item-remove-btn')) {
        target.parentElement.remove();
    }
    });

    newTodo.addEventListener(onkeydown, (event)=> {
    if (event.key === 'Enter') {
        addNewTodo()
    }
    })

    function addNewTodo() {
    if (newTodo.value) {
        const todoItem = document.createElement('li');
        todoItem.classList.add('todo-item');
        todoItem.innerHTML = `
            < input type = "checkbox" id = "todo-item-checkbox-${Date.now()}" class="todo-item-checkbox" >
            <label for="todo-item-checkbox-${Date.now()}" class="todo-item-label"><span></span> ${newTodo.value}/label>
            <button class="todo-item-remove-btn">Remove</button>
        `; 
        todoList.appendChild(todoItem);
        newTodo.value = '';
     }
    }

## English
Intermediate
