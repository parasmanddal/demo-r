<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8" />
        <meta  name="viewport" content="width=device,initial-scale=1.0"/>
        <title>age calculator</title>
    </head>
    <body>
        <div class="constant">
            <h1>age calculator</h1>
            <label for="birthdate">enter your birthdate</label>
            <input type="date" id="birthdate"/>
            <button onclick="calculateage()">calculate age</button>
            <p id="result"></p>
        </div>


        <script>
            function calculate age () {
                const birthdate= document.getElementById(" birthdate").value;
                const result1ement = document.getElementById("result");
                if (birthdate) {
                    const today =new date ();
                    const birthdate= new date (birthdate);
                    let ageyear = today. getfulyear()-birthdate.getfulyear();
                    let agemonths = today. getfulyear()-birthdate.getfulyear();
                    let agedays= today. getfulyear()-birthdate.getfulyear();
                    if (agedaysc<0){
                        agemonths--;
                        agedays+= new date(
                            today.getfulyear(),
                            today.getfulmonth(),
                            0
                        ).getdate();

                    }
                    if (agemonths <0){
                        ageyear--;
                        agemonths += 12;
                    }
                    
                    

                }
            }
        </script>
    </body>
</html>
