<!DOCTYPE html>
<html lang="en">
<html>
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        
        <title>2021 Cencus</title>
        
        <script type="text/javascript" src="jquery-3.5.1.min.js">
        // jQuery latest version 3.5.1
        </script>
        <script type="text/javascript" src="myscript.js">
        // My javascript function
        </script>
        <script type="text/javascript">
            $(initialise);
        </script>

        <link rel="stylesheet" type="text/css" href="style.css"/>
    </head>
    <body>
        <nav>
            <!----Navigation and Logo will be here---->
            <div class="nav-design">
                
                <img src="./images/au_logo3.png" alt="2021 Census information" width="100px" height="110px">
                
                <h2>2021 Census information</h2>
            </div>
            
        </nav>
        <div class="body-container">
            <!---body formating starts from here-->
            <section>
                <label>How many people spent the Census night at the dwelling?
                    <input id="totalPerson" type="number" name="numOfPeople" min="1" max="100"></label>
                    <input id="start" type="button" value="Start">
                    
                    

                        <h1>Personal details</h1>
                        <form action="https://tau.usq.edu.au/courses/CSC2406/reflect.php" id="form1" method="POST">
                                <!---Form section will be here---->
                            <fieldset id="fieldset1" class="fieldset1 show">
                                <legend>Person 1</legend>
                                <!---Q1-->
                                <p><label><span class="width">Given Name: </span>
                                <input id="gName1" type="text" name="givenName1" required size="20" pattern=" [a-zA-Z -]+ " /></label>
                                <span class="error hide">Please correct this field</span></p>
                                <!----Q2---->
                                <p><label><span class="width">Family Name:</span>
                                <input id="fName1" type="text" name="familyName1" required size="20" pattern=" [a-zA-Z -]+ "/></label>
                                <span class="error hide">Please correct this field</span></p>
                                <!---Q3-->
                                <p><label><span class="width" >Gender: </span>
                                    <select id="gender1" name="gender1">
                                        <option value=""> -- Please Select Gender -- </option>
                                        <option value="male">Male</option>
                                        <option value="female">Female</option>
                                        <option value="transgender">Transgender</option>
                                    </select> </label></p>

                                    <!----Q4 Year of Birth--->

                                    <p><label><span class="width">Year of Birth:</span>
                                        <select id=dob1 name="dob1">
                                            <option value="">-- Please Select Year --</option>
                                            <option value="1978">1978</option>
                                            <option value="1988">1988</option>
                                            <option value="1990">1990</option>
                                            <option value="1991">1991</option>
                                            <option value="1995">1995</option>
                                            <option value="1998">1998</option>
                                            <option value="1999">1999</option>
                                            <option value="2000">2000</option>
                                            <option value="2001">2001</option>
                                            <option value="2003">2003</option>
                                            <option value="2005">2005</option>
                                            <option value="2007">2007</option>
                                            <option value="2009">2009</option>
                                            <option value="2010">2010</option>
                                            <option value="2012">2012</option>
                                            <option value="2013">2013</option>
                                            <option value="2015">2015</option>
                                            <option value="2016">2016</option>
                                            <option value="2017">2017</option>
                                            <option value="2018">2018</option>
                                            <option value="2019">2019</option>
                                        </select>
                                        </label><span class="error hide">Please correct this field</span></p>

                                        <!---Q.5 Country of Birth -->

                                        <p><label><span class="width">Country of Birth:</span>                                                                  
                                                <!---List of Countries will be used in input element-->                                                                                      
                                            
                                            <select id="country1" name="birthPlace1" >
                                                <option>--Select Country--</option>
                                            
                                                    <optgroup label="Africa">                                                        
                                                        <optgroup label="Eastern Africa">
                                                            <option>Burundi</option>
                                                            <option>Burundi</option>
                                                            <option>Comoros</option>
                                                            <option>Djibouti</option>
                                                            <option>Eritrea</option>
                                                            <option>Ethiopia</option>
                                                            <option>Kenya</option>
                                                            <option>Madagascar</option>
                                                            <option>Malawi</option>
                                                            <option>Mauritius</option>
                                                            <option>Mayotte</option>
                                                            <option>Mozambique</option>
                                                            <option>Reunion</option>
                                                            <option>Rwanda</option>
                                                            <option>Seychelles</option>
                                                            <option>Somalia</option>
                                                            <option>Tanzania, United Republic of</option>
                                                            <option>Uganda</option>
                                                            <option>Zambia</option>
                                                            <option>Zimbabwe</option>
                                                        </optgroup>                                                           
                                                
                                                    <optgroup label="Middle Africa">
                                                        <option>Angola</option>
                                                        <option>Cameroon</option>
                                                        <option>Central African Republic</option>
                                                        <option>Chad</option>
                                                        <option>Congo (Brazzaville)</option>
                                                        <option>Congo, Democratic Republic of the</option>
                                                        <option>Equatorial Guinea</option>
                                                        <option>Gabon</option>
                                                        <option>Sao Tome and Principe</option>
                                                    </optgroup>                                                        
                                                
                                                    <optgroup label="Northern Africa">
                                                        <option>Algeria</option>
                                                        <option>Egypt</option>
                                                        <option>Libyan Arab Jamahiriya</option>
                                                        <option>Morroco</option>
                                                        <option>South Sudan</option>
                                                        <option>Sudan</option>
                                                        <option>Tunisia</option>
                                                        <option>Western Sahara</option>
                                                    </optgroup>                                                       
                                                
                                                    <optgroup label="Southern Africa">
                                                        <option>Botswana</option>
                                                        <option>Lesotho</option>
                                                        <option>Namibia</option>
                                                        <option>South Africa</option>
                                                        <option>Swaziland</option>
                                                    </optgroup>                                                       
                                                
                                                    <optgroup label="Western Africa">
                                                        <option>Benin</option>
                                                        <option>Burkina Faso</option>
                                                        <option>Cape Verde</option>
                                                        <option>Cote d'Ivoire (Ivory Coast)</option>
                                                        <option>Gambia</option>
                                                        <option>Ghana</option>
                                                        <option>Guinea</option>
                                                        <option>Guinea-Bissau</option>
                                                        <option>Liberia</option>
                                                        <option>Mali</option>
                                                        <option>Mauritania</option>
                                                        <option>Niger</option>
                                                        <option>Nigeria</option>
                                                        <option>Saint Helena</option>
                                                        <option>Senegal</option>
                                                        <option>Sierra Leone</option>
                                                        <option>Togo</option>
                                                    </optgroup>
                                                </optgroup>                                                    
                                            
                                                <optgroup label="----Asia---------">
                                                    <option>Afganistan</option>
                                                    <option>Armenia</option>
                                                    <option>Azerbaijan</option>
                                                    <option>Bangladesh</option>
                                                    <option>Bhutan</option>
                                                    <option>Brunei Darussalam</option>
                                                    <option>Cambodia</option>
                                                    <option>China</option>
                                                    <option>Georgia</option>
                                                    <option>Hong Kong</option>
                                                    <option>India</option>
                                                    <option>Indonesia</option>
                                                    <option>Japan</option>
                                                    <option>Kazakhstan</option>
                                                    <option>Korea, North</option>
                                                    <option>Korea, South</option>
                                                    <option>Kyrgyzstan</option>
                                                    <option>Laos</option>
                                                    <option>Macao</option>
                                                    <option>Malaysia</option>
                                                    <option>Maldives</option>
                                                    <option>Mongolia</option>
                                                    <option>Myanmar (ex-Burma)</option>
                                                    <option>Nepal</option>
                                                    <option>Pakistan</option>
                                                    <option>Phillipines</option>
                                                    <option>Singapore</option>
                                                    <option>Sri Lanka (ex-Ceilan)</option>
                                                    <option>Taiwan</option>
                                                    <option>Tajikistan</option>
                                                    <option>Thailand</option>
                                                    <option>Timor Leste (West)</option>                                 
                                                </optgroup>
                                            
                                            </select>
                                        </label><span class="error hide">Please correct this field</span>
                                        </p>
                                        <!----Q6 Arrive in Australia-->
                                        <p><label><span class="width">In what year did you arrive in Australia?</span>
                                            <select id="arrive1" name="arrival1">
                                                <option value="">-- Please Select Year of Arrival --</option>
                                                <option value="1978">1978</option>
                                                <option value="1988">1988</option>
                                                <option value="1990">1990</option>
                                                <option value="1991">1991</option>
                                                <option value="1995">1995</option>
                                                <option value="1998">1998</option>
                                                <option value="1999">1999</option>
                                                <option value="2000">2000</option>
                                                <option value="2001">2001</option>
                                                <option value="2003">2003</option>
                                                <option value="2005">2005</option>
                                                <option value="2007">2007</option>
                                                <option value="2009">2009</option>
                                                <option value="2010">2010</option>
                                                <option value="2012">2012</option>
                                                <option value="2013">2013</option>
                                                <option value="2015">2015</option>
                                                <option value="2016">2016</option>
                                                <option value="2017">2017</option>
                                                <option value="2018">2018</option>
                                                <option value="2019">2019</option>
                                            </select>                                                                                       
                                        </label><span class="error hide">Please correct this field</span></p>

                                        <!----Q.7 Citizenship--->
                                        <p><label><span class="width">Are you Australian Citizen?</span>
                                            <select id="citizen1" name="citizen1">
                                                <option value=""> -- Please Select your citizenship --</option>
                                                <option value="citizen">Yes, I am Australian Citizen</option>
                                                <option value="notCitizen">No, I am not Australian Citizen</option>
                                                <option value="pResident">I am Permanent Resident</option>
                                            </select>
                                        </label><span class="error hide">Please correct this field</span></p>

                                        <!---Q.8 Other Language-->
                                        <p> <label><span class="width">Do you  speak other than English?</span>
                                            <select id="langSpeak1" name="otherLang1">
                                                <option value=""> -- Other Language -- </option>
                                                <option value="engOnly">Englishl Only</option>
                                                <option value="mandarin">Mandarin</option>
                                                <option value="italian">italian</option>
                                                <option value="arabic">Arabic</option>
                                                <option value="cantonese">Cantonese</option>
                                                <option value="greek">Greek</option>
                                            </select>
                                        </label><span class="error hide">Please correct this field</span></p>    

                                        <!----Q.9 Language Proficiency-->

                                        <p><label id="proficiency1"><span class="width">How well do speak English?</span></label>
                                            <label><input type="radio" name="nevigation" value="veryWell"/>Very Well</label>
                                            <label><input type="radio" name="nevigation" value="Well"/>Well</label>
                                            <label><input type="radio" name="nevigation" value="notWell"/>Not Well</label>
                                            <label><input type="radio" name="nevigation" value="notAtAll"/>Not at All</label>
                                        <span class="error hide">Please correct this field</span></p>

                                        <!---Question 10 [Secondary school]-->

                                        <p><label><span>What is the highest year of secondary school the person has completed?</span>
                                            <select id="school1" name="secondarySchool1">
                                                <option value=""> -- Choose your Highest year--</option>
                                                <option value="year6">Year 6</option>
                                                <option value="year7">Year 7</option>
                                                <option value="year8">Year 8</option>
                                                <option value="year9">Year 9</option>
                                                <option value="year10">Year 10</option>
                                                <option value="year11">Year 11</option>
                                                <option value="year12">Year 12</option>                        
                                            </select>
                                        </label><span class="error hide">Please correct this field</span></p>

                                        <!---Question 11 [Higest Qualification]-->

                                        <p><label><span>What is the highest qualification you have received?</span>
                                            <select id="highQ1" name="qualification1">
                                                <option value=""> -- Choose your Highest qualificaiton--</option>
                                                <option value="trade">Trade Certificate</option>
                                                <option value="cert1">Cert. I</option>
                                                <option value="cert2">Cert. II</option>
                                                <option value="cert3">Cert. III</option>
                                                <option value="cert4">Cert. IV</option>
                                                <option value="bachelor">Bachelor Degree</option>
                                                <option value="masters">Masters Degree</option>
                                                <option value="diploma">Diploma</option>                        
                                            </select>
                                        </label><span class="error hide">Please correct this field</span></p>

                                        <!---Question 12 [Field of Study]--->

                                        <p><label><span>What is the main field of study of your Highest qualification</span> <!--here we can use nested list-->
                                        <select id="studyArea1" name="fieldOfStudy1">
                                            <option value=""> -- Choose field of qualificaiton--</option>
                                            <option value="science">Science & Technology</option>
                                            <option value="agri">Agriculture</option>
                                            <option value="chem">Chemistry</option>
                                            <option value="physics">Physics</option>
                                            <option value="civil">Civil Engineering</option>
                                            <option value="medi">Medical</option>
                                            <option value="geo">Geography</option>
                                            <option value="edu">Education</option>                        
                                        </select>
                                    </label><span class="error hide">Please correct this field</span></p>


                                    <p><label>
                                       <button  id="btn1" type="button" name="btn1" value="Continue"> Next btn</button> <!---but this has to be js validtion -->   
                                    </label></p>

                            </fieldset>
                            <br>
                            <!----Part II---->

                            <fieldset class="fieldset1 show">
                                <legend>The Dwelling</legend>
                                <!----Q.1-->

                                <p><label><span class="width">Type of Dwelling:</span> 
                                    <select id="dwell" name="dwell">
                                        <option value=""> -- Dwelling type--</option>
                                        <option value="detachHouse">Detached House</option>
                                        <option value="semiDetHouse">Semi-Detach House</option>
                                        <option value="apart">Apartment</option>
                                        <option value="retirement">Retirement</option>
                                        <option value="village">Village</option>
                                        <option value="caraven">Caraven</option>
                                        <option value="houseBoat">House boat</option>

                                    </select>
                                </label><span class="error hide">Please correct this field</span></p>

                                <!----Q2.-->
                                <p><label><span class="width">Is this dwelling:</span>
                                    <select id="dwellAquire" name="ownership">
                                        <option value=""> -- Choose your answer--</option>
                                        <option value="outright">Owned outright</option>
                                        <option value="mortgage">Owned with mortgage</option>
                                        <option value="rented">Rented</option>
                                        <option value="rentFree">Rent Free</option>
                                                                
                                    </select>
                                </label><span class="error hide">Please correct this field</span></p>

                                <!---Q3-->
                                <p><label><span class="width">Source of energy for this dwelling:</span>
                                    <select id="electricity" name="energy">
                                        <option value=""> -- Choose your answer--</option>
                                        <option value="elec">Mains electricity</option>
                                        <option value="photoPanel">Photovoltaic Panels</option>
                                        <option value="battery">Battery</option>
                                        <option value="gas">Gas</option>
                                        <option value="noPower">No Power source</option>
                                        
                                    </select>
                                </label><span class="error hide">Please correct this field</span></p>

                                <!---Q4-->
                                <p><label><span class="width">Internet access for the dwelling:</span>
                                    <select id="internet" name="internet">
                                        <option value=""> -- Choose your answer--</option>
                                        <option value="fibeHouse">Fiber to the house</option>
                                        <option value="fiberCurb">Fiber to the curb</option>
                                        <option value="fiberNode">Fiber to the Node</option>
                                        <option value="wireless">fixed Wireless</option>
                                        <option value="noInter">No Internet</option>
                                        
                                    </select>
                                </label><span class="error hide">Please correct this field</span></p>

                                <!---Q5-->
                                <p><label><span class="width"> Average monthly internet download</span>
                                    <input id="intUse" type="number" name="intUse" min="0" max="500">GB</label>
                                    <span class="error hide">Please correct this field</span></p>
                                
                                <!---Q6-->
                                <p><label><span class="width"> How many bedrooms in the dwelling?</span>
                                    <input id="rooms" type="number" name="rooms" min="0" max="20"></label>
                                    <span class="error hide">Please correct this field</span></p>
                                
                                <!----Q7-->

                                <p><label id="elecCar"><span class="width">Are there any electric vehicles garaged at the dwelling?</span></label>
                                    <label><input type="radio" name="elecCar" value="yes"/>Yes</label>
                                    <label><input type="radio" name="elecCar" value="no"/>No</label>
                                <span class="error hide">Please correct this field</span></p>

                                <p><label><span class="width">If yes: What type of car:</span>
                                    <select id="garagedElecCar" name="garaged">
                                        <option value=""> -- Choose your answer--</option>
                                        <option value="hybridCar">Hybrid-car</option>
                                        <option value="suv">SUV</option>
                                        <option value="suvHybrid">Fiber to the Node</option>
                                        <option value="hybridTruck">Hybrid-truck</option>
                                        <option value="schooti">Schooter</option>
                                        
                                    </select>
                                </label><span class="error hide">Please correct this field</span></p>
                            </fieldset>
                            <br>

                            <fieldset class="rating">
                                <legend>Rating Questionnaire</legend>

                                <!---Q1-->
                                <p>For possible follow-up questions please supply a contact - phone or email address:</address></p>
                                <p><label><span class="width">Phone: </span>
                                    <input id="phone" type="tel" name="phoneNum" pattern=" [0-9]{10} " /></label>
                                    <span class="error hide">Please correct this field</span></p>

                                <p><label><span class="width">Email: </span>
                                    <input id="email" type="email" name="email"  pattern=" [a-zA-Z0-9-_]+@[a-zA-Z0-9_-]\.[a-zA-Z] " /></label>
                                    <span class="error hide">Please correct this field</span></p>

                                <!--Q2-->
                                <p><label id="diff"><span class="width">How difficult was this Questionnaire to nevigate</span></label>
                                    <label><input type="radio" name="nevigation" value="veryhard"/>Very Hard</label>
                                    <label><input type="radio" name="nevigation" value="hard"/>Hard</label>
                                    <label><input type="radio" name="nevigation" value="ok"/>OK</label>
                                    <label><input type="radio" name="nevigation" value="easy"/>Easy</label>
                                <span class="error hide">Please correct this field</span></p>

                                <!--Q3-->
                                <p><label id="useful"><span class="width">Did you find the help useful:</span></label>
                                    <label><input type="radio" name="help" value="yes"/>Yes</label>
                                    <label><input type="radio" name="help" value="no"/>No</label>
                                    <label><input type="radio" name="help" value="noUse"/>Did not use</label>                                    
                                <span class="error hide">Please correct this field</span></p>

                                <!---Q4-->
                                <p><label><span class="width">Any other comments: </span>
                                    <textarea rows="4" cols="50" name="comment">Enter your comments here...</textarea>
                                    </label></p>

                            </fieldset>
                            <br>

                        </form>                        
                         
                   
                   
                    <p><input type="submit" form="form1" name="submit1" value="submit"> </p> <!---Actuall submit button--->

                   
                   
                    
            </section>
            
            </div>

            <footer>
                <!-- Footer will go here [ this section borrowed from Assignment 1]
                Copy Right information & Contacts-->
                <div class="footer-row">
                    <div class="footer-col">
                        <p>Links</p>
                        <a href="index.html">Home</a></br>
                        <a href="author.html">Austhors</a></br>
                        <a href="aboutus.html">About us</a></br>
                        <a href="contact.html">Contact us</a>
                    </div>
                    <div class="footer-col">
                        <p>Contact us</p>
                        <Address>134 Hill Road
                            RunCcorn, QLD 4113
                            Australia
                        </Address>
                        <p>Phone: +61 07 234 567</p>
                    </div>
                </div>
                <div class="copyright">copyright &#169; 2020-2021 by Hornshell. All rights reserved</div>
            </footer>
            
        </body>
    </html>
