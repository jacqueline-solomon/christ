<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF_8">
        <meta name="viewport" content="width=device-width,initial-scale.0">
        <title>1.Task</title>
        <style>
            table,th,td {
                border: 1px;
            }
        </style>
    </head>
    <body>
        <h1>Task 1</h1>
        <div>
            <h2>1.APPLICATION FORM</h2>
            <form action=""> 
                <div>
                <label for="Name">Name : </label>
                    <input type="type" placeholder="Enter your name :"><br>
                    </div>
                 <div>  
                <label for="Email">Email :</label>
                <input type="text" placeholder="Enter your Email :"><br>
                </div>
                <div>
                <label for="Gender"> Gender :</label>
                <input type="radio" value="Male"> Male
                <input type="radio" value="Female">Female 
            </div>
            <br>
                <div>
                    <label for="Skill">choose skill :</label>
                    <input type="checkbox" value="Html"> html
                    <input type="checkbox" value="css">css
                    <input type="checkbox" value="Bootstrap">Bootstrap
                    <input type="checkbox" value="Javascript">Javascript
                    <input type="checkbox" value="React">React
                                </div> <br>
                <div>
                    <label for="Job Type">Job Type :</label>
                    <select name="Front End" id="">
                        <option value="Front End Developer">Front End Developer</option>
                        <option value="Back End Develpoer">Back End Developer</option>
                        <option value="Mobile Application Develpoer">Mobile Application Developer</option>
                        <option value="Full Stack Develpoer"> Full Stack Develpoer </option>
                        <option valuue="Software Tester"> Software Tester</option>
                    </select>
                </div>
                <br>
                <div>
                    <label for="Name"> Choose your browser from the list :</label>  
                <input type="text" placeholder="">
                      </div>
                      <br>
                      <div>
                        <textarea rows="2" cols="20" neme="Message form=useform">Give a brief about yourself</textarea>

                 </div> <br>
                 <div>
                    <button>submit</button>
                 </div>              

            </form>
        </div>
        <hr>
        <div>
            <h2> 2.BATCH LIST</h2>
            <ul>
                <li>
                    <h4>Senchola University</h4>
                </li>
                </ul>
                
                    <li>First Batch</li>
                    <br>
                    <ol type="A">
                        <li>Ravi</li>
                        <li>Manoj</li>
                        <li>Sandhiya</li>
                    </ol>
                
                <br>
                
                <li>Second Batch</li>
                <br>
                <ol type="I">
                    <li>Sundar</li>
                    <li>Saranya</li>
                    <li>Nandhini</li>
                </ol>
                
                    <br>
                    
                    <li>Third Batch</li>
                    <br>
                    <ol type="i">
                        <li>Monika</li>
                        <li>Santhose</li>
                        <li>Kannan</li>
                    </ol>
                    
                </ul>
            <h2>3.COURSES</h2>
            <table style="width:30%";>
                <tr>
                    <th> S.NO 1 </th>
                    <th> S.NO 2 </th> 
                    <th> S.NO 3 </th>  
                    <th> S.NO 4 </th>    
                 </tr>
                 <tr>
                    <td rowspan="2">React JS</td>
                    <td> Html</td>
                    <td rowspan="2">React JS</td>
                    <td>Css</td>
                 </tr>
                 <tr>
                    <td>Css</td>
                    <td>Html</td>
                 </tr>
                 <tr>
                    <td colspan="2">Javascript</td>
                    <td colspan="2"> Bootstrap</td>
                 </tr>
            </table>
            </div>
    </body>
</html>
