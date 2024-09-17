# JavaScript_project
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}


body {
    background: #41295a;
}

.wrapper {
    background-color: #fff;
    width: 700px;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    padding: 40px;
    border-radius: 10px;
    text-align: center;
    box-shadow: 0 10px 20px 0px rgba(0, 0, 0, 0.15);
    z-index: -1;
}

.wrapper h2 {
    font-size: 32px;
    margin-bottom: 40px;
    font-family: "Philosopher", sans-serif;
}


.heading::after {
    content: '';
    width: 160px;
    height: 3px;
    border-radius: 3px;
    background-color: #41295a;
    position: absolute;
    top: 100px;
    left: 50%;
    transform: translateX(-50%);
}

blockquote {
    font-size: 26px;
    min-height: 60px;
    font-family: "Mulish", sans-serif;
    margin: 25px 0;
}

blockquote::before,
blockquote::after {
    content: '"';
}

.author {
    display: block;
    margin-top: 10px;
    float: right;
    position: relative;
    font-weight: bold;
    font-family: "Philosopher", sans-serif;
}

.author::before {
    content: '';
    width: 20px;
    height: 2px;
    background-color: #41295a;
    position: absolute;
    top: 50%;
    left: -30px;
}

.buttons {
    width: 100%;
    margin-top: 50px;
    display: flex;
    justify-content: center;
    font-family: "Philosopher", sans-serif;
}

.buttons button {
    background-color: #41295a;
    color: #fff;
    border-radius: 10px;
    border: 1px solid #41295a;
    width: 125px;
    height: 50px;
    display: flex;
    justify-content: center;
    align-items: center;
    margin: 5px;
    cursor: pointer;
    font-size: 15px;
}

.buttons button i {
    margin-right: 10px;
    font-size: 20px;
}
