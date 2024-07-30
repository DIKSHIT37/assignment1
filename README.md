<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        table,th,td{
        border: 1px solid black;
      }
      </style>
</head>
<body>
    <header> 
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#news">News</a></li>
            <li><a href="#contact">Contact</a></li>
            <li><a href="#about">About</a></li>
      </ul>
      <hr>
      <hr>
    </header>
   
    <div id="Heading_tag">
        <h1>h1: Heading Tag</h1>
        <h2>h2: Heading Tag</h2>
        <h3>h3: Heading Tag</h3>
        <h4>h4: Heading Tag</h4>
        <h5>h5: Heading Tag</h5>
        <h6>h6: Heading Tag</h6>
    </div>
      
    <div id="Formatting-Elements">
        <h1><u>Formatting Elements</u></h1><br>
        <b>Bold Text</b><br>
        <strong>Strong Text</strong><br>
        <i>Italic Text</i><br>
        <em>Emphasized Text</em><br>
        <mark>Mark text</mark><br>
        <p> This is <sub>subscripted</sub> text. </p>
        <p>This is <sup>Superscripted</sup> text.</p>
     </div>

     <div id="Image">
        <h1><u>Image</u></h1>
        <aside style="float: right; width: 30%;"><p>In botany, a tree is a perennial plant with an elongated stem, or trunk, usually supporting branches and leaves. In some usages, the definition of a tree may be narrower, including only woody plants with secondary growth, plants that are usable as lumber or plants above a specified</p></aside>
        <img src="img.jpg" alt="tree" height="200px" width="200px">
    </div>
    <br>
    <div id="Table">
        <table style="width: 200px; ">
            <tr><th colspan="3">Table</th></tr>
            <tr style="height: 30px;">
                <th></th>
                <th></th>
                <th></th>
            </tr>
            <tr style="height: 30px;">
                <th></th>
                <th></th>
                <th></th>
            </tr>
            <tr style="height: 30px;">
                <th></th>
                <th></th>
                <th></th>
            </tr>
        </table>
        
        <aside>
            <table style="float: right; width: 10%;">
                <tr><th>Title</th></tr>
                <tr>
                    <td>section 1.1<br>
                        section 1.2<br>
                        section 1.3<br>
                    </td>
                </tr>
                <tr>
                    <td>section 2.1<br>
                        section 2.2<br>
                        section 2.3<br>
                    </td>
                </tr>
            </table>
        </aside>
        </div>

     <div id="form">
        <h1><u>form element</u></h1>
        <form>
            <label for="Name">Name:</label>
            <input type="text" name="Name"><br>

            <h3>Radio Buttons</h3>
            <input type="radio"  value="HTML">
            <label for="html">HTML</label><br>

            <h3>Check box</h3>
            <input type="checkbox"  value="html">
            <label for="html"> I know html</label>

            <h3>Button</h3>
            <button>click me!</button>
          </form>
     </div>

     <div id="html_media">
        <h1>html media</h1>
        <video width="320" height="140" autoplay>
            <source src="movie.mp4" type="video/mp4">
        </video>

        <h4>audio</h4>
        <audio controls>
           <source src="horse.mp3" type="audio/mpeg">
        </audio>

        <h4>YouTube</h4>
        <iframe width="420" height="315"
            src="https://www.youtube.com/embed/tgbNymZ7vqY?autoplay=1&mute=1">
        </iframe>
     </div>

     <footer>
        <h2>footer</h2>
        <table style="width: 100%; ">
            
            <tr style="height: 50px;">
                <th>value1</th>
                <th>value2</th>
                <th>value3</th>
            </tr>
            <tr style="height: 50px;">
                <th>value4</th>
                <th>value5</th>
                <th>value6</th>
            </tr>
            <tr style="height: 50px;">
                <th>value7</th>
                <th>value8</th>
                <th>value9</th>
            </tr>
        </table>
     </footer>
</body>
</html>
