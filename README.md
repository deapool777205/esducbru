/* Reset básico */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f9;
    color: #333;
}

header {
    background-color: #007BFF;
    color: white;
    padding: 1rem 0;
}

nav ul {
    display: flex;
    justify-content: center;
    list-style: none;
}

nav ul li {
    margin: 0 1rem;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

main {
    text-align: center;
    padding: 2rem;
}

.btn {
    display: inline-block;
    margin-top: 1rem;
    padding: 0.8rem 1.5rem;
    background-color: #28a745;
    color: white;
    text-decoration: none;
    border-radius: 5px;
}

footer {
    text-align: center;
    padding: 1rem;
    background-color: #333;
    color: white;
    position: fixed;
    bottom: 0;
    width: 100%;
}
