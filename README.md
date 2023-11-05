<!DOCTYPE html>
<html>
<head>
    <link rel="stylesheet" type="text/css" href="akm.css">
    
</head>
<body>

    <h1>Our Menu</h1>
    <section class="section">
        <div class="section-title">Chicken</div>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit,sed doeiusmod tempor ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamvo laboris nisi ut aliquip nisi ex ea commodo consequat.</p>
    </section>
    <section class="section">
        <div class="section-title">Beef</div>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit,sed doeiusmod tempor ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamvo laboris nisi ut aliquip nisi ex ea commodo consequat.</p>
    </section>
    <section class="section">
        <div class="section-title">Sushi</div>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit,sed doeiusmod tempor ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamvo laboris nisi ut aliquip nisi ex ea commodo consequat.</p>
    </section>
</body>
</html>


/* Reset some default styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
}

 h1{
    text-align: ;
 }

/* Define breakpoints */
@media screen and (min-width: 992px) {
    .section {
        width: 33.33%;
        float: left;
    }
}

@media screen and (min-width: 768px) and (max-width: 991px) {
    .section {
        width: 50%;
        float: left;
    }

    .section:nth-child(3) {
        width: 100%;
        clear: both;
    }
}

@media screen and (max-width: 767px) {
    .section {
        width: 100%;
    }
}

/* Common styles for all views */
.section {
    background-color: #f2f2f2;
    border: 1px solid #000;
    margin: 10px;
    padding: 10px;
    position: relative;
}

.section-title {
    background-color: #666;
    color: #fff;
    position: absolute;
    top: 0;
    right: 0;
    padding: 10px 10px;
}



