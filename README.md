style.css
/* General Styles */
body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background-color: #f5f7fa;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    color: #333;
}

/* Login Container */
.login-container {
    background-color: white;
    border-radius: 10px;
    box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
    padding: 40px;
    width: 100%;
    max-width: 400px;
    box-sizing: border-box;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.login-container:hover {
    box-shadow: 0 15px 35px rgba(0, 0, 0, 0.15);
    transform: translateY(-5px);
}

.login-container h2 {
    margin: 0 0 30px 0;
    text-align: center;
    color: #2c3e50;
    font-weight: 600;
}

/* Form Elements */
form {
    display: flex;
    flex-direction: column;
}

.input-group {
    margin-bottom: 20px;
}

.input-group label {
    display: block;
    margin-bottom: 8px;
    font-weight: 500;
    color: #555;
}

.input-group input {
    width: 100%;
    padding: 12px 15px;
    border: 1px solid #ddd;
    border-radius: 6px;
    font-size: 16px;
    transition: border-color 0.3s ease, box-shadow 0.3s ease;
    box-sizing: border-box;
}

.input-group input:focus {
    border-color: #3498db;
    box-shadow: 0 0 0 3px rgba(52, 152, 219, 0.2);
    outline: none;
}

/* Button Styles */
button {
    background-color: #3498db;
    color: white;
    border: none;
    padding: 14px;
    border-radius: 6px;
    font-size: 16px;
    font-weight: 500;
    cursor: pointer;
    transition: background-color 0.3s ease, transform 0.2s ease;
    margin-top: 10px;
}

button:hover {
    background-color: #2980b9;
    transform: translateY(-2px);
}

button:active {
    transform: translateY(0);
}

/* Responsive Design */
@media (max-width: 480px) {
    .login-container {
        padding: 30px 20px;
        margin: 0 15px;
    }
}

