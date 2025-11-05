# E-commerce-
 
<!DOCTYPE html>
<html lang="en">
<head>
<style>
    /* The animation 'pulse' */
    @keyframes pulse {
        0% {
            transform: scale(1);       /* Start at normal size */
            box-shadow: 0 0 0 0 rgba(0, 123, 255, 0.7);
        }
        70% {
            transform: scale(1.05);  /* Grow slightly */
            box-shadow: 0 0 0 10px rgba(0, 123, 255, 0);
        }
        100% {
            transform: scale(1);       /* Return to normal size */
            box-shadow: 0 0 0 0 rgba(0, 123, 255, 0);
        }
    }

    /* The button styling */
    .myButton {
        padding: 15px 30px;
        font-size: 16px;
        color: white;
        background-color: #007bff; /* Blue */
        border: none;
        border-radius: 5px;
        cursor: pointer;
        
        /* This line applies the 'pulse' animation */
        animation: pulse 2s infinite; 
    }
</style>
</head>
<body>

<h2>Pulsing Button Animation</h2>
<button class="myButton">Click Me!</button>

</body>
</html>
