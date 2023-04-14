# Fun with CSS

-   Amateur
-   By:  Guillaume, CTO at Holberton School
-   Weight:  1

In this project, you will experiment and implement fun layout with HTML and CSS  **ONLY**!

Yes, no JavaScript!

Enjoy!

## Tasks

### 0. Sprite languages

#advanced

By using this HTML:

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <title>HBTN - 0- Sprite</title>

        <link href="0-styles.css" media="all" rel="stylesheet" type="text/css">
    </head>
    <body>
        <ul>
            <li>HTML<span class="icon i-html"></span></li>
            <li>CSS<span class="icon i-css"></span></li>
            <li>JavaScript<span class="icon i-js"></span></li>
        </ul>
    </body>
</html>

```

And this image file:  [0-sprite.png](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/2/d416199ca6ecdbd0f8a3.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230413%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230413T112332Z&X-Amz-Expires=345600&X-Amz-SignedHeaders=host&X-Amz-Signature=048b77b6b38f7bb08821adafd5f56b8a35ee18c378dc94ae627491dfc7847b83 "0-sprite.png")

Create  `0-styles.css`  and generate this layout:

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/2/94aa60f76c412f40a87b.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230413%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230413T112332Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=d10600eca360db9a09f93807a36febfdc2bd71619fd077a3a6b39b180c0aa508)

You are not allowed to change the image and the HTML -  _sprite is cool!_

**Repo:**

-   GitHub repository:  `holbertonschool-Fun-with-CSS`
-   File:  `0-styles.css`

Please review your task manually with the following checklist

[](https://intranet.hbtn.io/projects/2390#task-21917-carousel)

Readme is present and not empty

[](https://intranet.hbtn.io/projects/2390#task-21917-carousel)

Help

**0/14** pts

### 1. Move the (under)line

#advanced

By using this HTML:

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <title>HBTN - 1- Underline</title>

        <link href="1-styles.css" media="all" rel="stylesheet" type="text/css">
    </head>
    <body>
        <h2>
            Hello <a href="https://www.holbertonschool.com">Holberton!</a>
        </h2>
    </body>
</html>

```

Create  `1-styles.css`  and generate this layout where the underline is hidden by default and appeared slowly…:

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/2/b791cfdbd11c0eefa5f7.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230413%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230413T112332Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=2ded1ea9c6d777b2eed4f6751b6cba6314bda9da946b82eb513a006ae93346ec)

You are not allowed to change the HTML

**Repo:**

-   GitHub repository:  `holbertonschool-Fun-with-CSS`
-   File:  `1-styles.css`

Please review your task manually with the following checklist

[](https://intranet.hbtn.io/projects/2390#task-21918-carousel)

File exists

[](https://intranet.hbtn.io/projects/2390#task-21918-carousel)

Help

**0/8** pts

### 2. Toggle

#advanced

By using this HTML:

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <title>HBTN - 2- toggle</title>

        <link href="2-styles.css" media="all" rel="stylesheet" type="text/css">
    </head>
    <body>
        <div class="toggle">
            <input type="checkbox" name="toggle" class="toggle-cb" id="toggle-0" checked>
            <label class="toggle-label" for="toggle-0">
                <div class="toggle-inner"></div>
                <div class="toggle-switch"></div>
            </label>
        </div>
    </body>
</html>

```

Create  `2-styles.css`  and generate this layout where the  `<input>`  is has this custom toggle layout:

**Checked:**

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/2/3848b025c8f25636bba5.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230413%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230413T112332Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=49134f80f102a0db3d430137c193a3f85b4be4d0c053f0e1e2ce0453f8519f5e)

**Unchecked:**

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/2/aeae59fdee93b17f360f.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230413%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230413T112332Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=de5d4dc1e3b95653513faf158e1f62fe617848e57edd48fc5b0e749c99231beb)

You are not allowed to change the HTML

**Repo:**

-   GitHub repository:  `holbertonschool-Fun-with-CSS`
-   File:  `2-styles.css`

Please review your task manually with the following checklist

[](https://intranet.hbtn.io/projects/2390#task-21919-carousel)

File exists

[](https://intranet.hbtn.io/projects/2390#task-21919-carousel)

Help

**0/11** pts

### 3. Menu

#advanced

By using this HTML:

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <title>HBTN - 2- toggle</title>

        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
        <link href="3-styles.css" media="all" rel="stylesheet" type="text/css">
    </head>
    <body>

        <nav class="menu">
            <input type="checkbox" href="#" class="menu-open" name="menu-open" id="menu-open"/>
            <label class="menu-open-button" for="menu-open">
                <span class="menu-line menu-line-1"></span>
                <span class="menu-line menu-line-2"></span>
                <span class="menu-line menu-line-3"></span>
            </label>

            <a href="#" class="menu-item"> <i class="fa fa-area-chart"></i> </a>
            <a href="#" class="menu-item"> <i class="fa fa-bar-chart"></i> </a>
            <a href="#" class="menu-item"> <i class="fa fa-line-chart"></i> </a>
            <a href="#" class="menu-item"> <i class="fa fa-pie-chart"></i> </a>
            <a href="#" class="menu-item"> <i class="fa fa-table"></i> </a>
        </nav>

    </body>
</html>

```

Create  `3-styles.css`  and generate this layout/animation:

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/2/252a25667dc7c65fe0e9.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230413%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230413T112332Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=388fe76a726be0596784e316a74f072ecad548ba7005e6a81e68c5b04e7f0a47)

You are not allowed to change the HTML

**Repo:**

-   GitHub repository:  `holbertonschool-Fun-with-CSS`
-   File:  `3-styles.css`
