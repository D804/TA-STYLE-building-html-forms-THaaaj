- Create a forms according to the layout shown below.

![Building HTML forms Assignment level 1](https://raw.githubusercontent.com/suraj122/AC-STYLE-images/master/building-html-forms/ex-1.jpg)

- Using CSS resets is necessary.

- Use semantic tags and keep the nesting and indentation proper.
<!--HTML CODE-->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="assets/stylesheet/style.css">
    <!--Google Fonts-->
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Sulphur+Point:wght@300;400;700&display=swap" rel="stylesheet">

</head>
<body>
    <main>
        <section>
            <img class="bg-img" src="assets/media/bg-intro-desktop.png" alt="Loading error">
            <div class="container">
                <div class="col flex">
                    <div class="col-1">
                       <h1 class="heading">Learn to code by watching others</h1>
                       <p class="heading-para">Lorem ipsum dolor sit amet consectetur adipisicing elit. Eaque totam quidem possimus exercitationem! Hic ex optio a </p>
                    </div>
                    <div class="col-2 ">
                        <form action="index.html" method="post">
                            <h2 class="form-heading"><span class="demo">Try it free 7 days</span> then $20/mo.thereafter </h2>
                            <fieldset class="background">
                                <label>
                                    <input class="form-control" type="text" name="username" placeholder="First Name">
                                </label>
                                <label>
                                    <input class="form-control" type="text" name="username" placeholder="Last Name">
                                </label>
                                <label>
                                    <input class="form-control" type="email" name="email-address" placeholder="Email-Address">
                                </label>
                                <label>
                                    <input class="form-control" type="password" name="password" placeholder="password">
                                </label>
                                <button class="form-control btn" name="submit">CLAIM YOUR FREE TRIAL</button>
                                <h3>By clicking the button,you are agreeing to our<span class="criteria"> Term and Services </span></h3S>
                            </fieldset>
                        </form>
                    </div>
                </div>

            </div>
        </section>
    </main>
</body>
</html>