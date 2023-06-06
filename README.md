# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:
### Step 1 : Clone the github repository and create a django admin interface
### Step 2 :  Write HTML and CSS for designing book cover page and execute them .
### Step 3 : Validate the HTML and CSS code.
### Step 4 : Publish the website in the given URL.

## Code:
cover.html:
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Unlock Your Inner Giga Chad</title>
        <style>
        h1{
           color:rgb(0, 255, 213);
        }
         .bookpage{
             width: 400px;
             height: 650px;
             background-color: greenyellow;
             background-position: center;
             margin-left: auto;
             margin-right: auto ;
             padding: 20px;
             background-image: url("bkcr.jpg");
             background-size: cover;
             background-repeat: no-repeat;

         }
         .toptext{
             color:rgb(247, 255, 9);
             padding-left: 10px;
             font-size: 14px;
             font-family: Arial, Helvetica, sans-serif;

         }
         .tophr{
             color:#e36f2f;
              width: 180px;
         }
         hr{
             color:#e36f2f;

         }
         .booktitle{
             font-family: Arial, Helvetica, sans-serif;
             padding: 10px 10px 0px 10px;
             display: flex;
            align-items: center;
            justify-content: center;
  margin-right: 10px;
  margin-left: 10px;
  font-size: 20px;
         }
         .author{
             color:white;
             font-family: Arial, Helvetica, sans-serif;
             display: inline;
             font-size: 24px;
             position:relative;
             line-height: 20px;


         }
         .sub-text {
             color:white;
             font-family: Arial, Helvetica, sans-serif;
             display: flex;
             line-height: 5px;

  margin-right: 10px;
  margin-left: 10px;

  font-size: 14px;
  }

.footer {
  color:orange;
  padding-top: 180px;
}
.image {
    color:white;
             font-family: Arial, Helvetica, sans-serif;
 font-size: 22px;
  margin-right: 20px;
}
.bottomhr {
    color:#e36f2f;
              width: 400px;

}
img {
    width: 90px;
    height: 100px;
    margin-right: 20px;
    vertical-align: bottom;
}
.edition {
    color:#e36f2f;
             font-family: Arial, Helvetica, sans-serif;
 font-size: 22px;
 line-height:bottom;

}


        </style>
        </head>
            <body>
                <div class="bookpage">

                    <div class="toptext">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;BEGINNER FRIENDLY</div>
                    <div class="tophr"><hr></div>
               <div class="booktitle"><h1>Turn into GIGA CHAD in a week!</h1></div>
               <h3 class="sub-text">We go gym!</h3>
                    <h3 class="sub-text">written by Sudharsanam R K</h3>
                    <div class="footer">
                        <h2 class="edition">&nbsp;&nbsp;First
Edition&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  <img src="legit me.jpg" alt="Author"></h2>

                        <div class="bottomhr"><hr></div>
                    <div class="author"><h3>&nbsp;&nbsp;SudharsanamRK &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</h3></div>

                </div>
                </div>

            </body>


</html>
```

## Output:

![image](https://github.com/prabhjot-singh18/cover-page-design/assets/121215854/c9162b48-2b90-4664-86c2-fa38d70e8d29)
## Result:
Thus the program to develop a website to display the cover page design of a book has been successfully executed.
