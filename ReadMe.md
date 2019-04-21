# This is my attempt to learning the CSS Box Model

> Learned below

* <code>box-sizing: border-box</code>
* merged margins will only consider the largest among them

* A list item with code block

<code> 

       * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body > h1 {
            margin-bottom: 100px;
        }

        div {
            width: 600px;
            height: 200px;
        }
    
        .first-box {
            padding: 10px;
            border: 10px solid gray;
            background-color: blueviolet;
            margin-bottom: 10px;
            
        }

        .second-box {
            padding: 10px;
            color: white;
            background-color: black;
            border: 10px solid red;
        } 
</code>