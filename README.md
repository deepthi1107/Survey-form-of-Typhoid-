<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>

    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.1/dist/css/bootstrap.min.css" integrity="sha384-zCbKRCUGaJDkqS1kPbPd7TveP5iyJE0EjAuZQTgFLD2ylzuqKfdKlfG/eSrtxUkn" crossorigin="anonymous">

    <style>
        body{
            background-color: #ebf3ff;
        }
        h3{padding-bottom: 30px;}
    </style>

</head>
<body>

    <div class="container my-5">
        <form action="#" method="post" class="card" name="google-sheet">
        <ul class="list-group list-group-flush">
            <div class="list-group-item">
                <h3 class="mt-4 text-center">Patient's Information</h3>
                    
                <div class="form-group row">
                    <label for="name" class="col-sm-2 col-form-label">Name</label>
                    <div class="col-sm-10">
                        <input type="text" class="form-control" id="name">
                    </div>
                </div>
                <div class="form-group row">
                    <label for="age" class="col-sm-2 col-form-label">Age</label>
                    <div class="col-sm-10">
                        <input type="number" class="form-control" id="age">
                    </div>
                </div>
                <div class="form-group row">
                    <label for="weight" class="col-sm-2 col-form-label">Weight</label>
                    <div class="col-sm-10">
                        <input type="number" class="form-control" id="weight">
                    </div>
                </div>
                <div class="form-group row">
                    <label for="height" class="col-sm-2 col-form-label">Height</label>
                    <div class="col-sm-10">
                        <input type="number" class="form-control" id="height">
                    </div>
                </div>

                <fieldset class="form-group row">
                    <legend class="col-form-label col-sm-2 float-sm-left pt-0">Blood Pressure</legend>
                    <div class="col-sm-10">
                        <div class="form-check">
                            <input class="form-check-input" type="radio" name="bloodPressure" id="bp1" value="No BP">
                            <label class="form-check-label" for="bp1">
                            No BP
                            </label>
                        </div>
                        <div class="form-check">
                            <input class="form-check-input" type="radio" name="bloodPressure" id="bp2" value="High BP">
                            <label class="form-check-label" for="bp2">
                            High BP
                            </label>
                        </div>
                        <div class="form-check disabled">
                            <input class="form-check-input" type="radio" name="bloodPressure" id="bp3" value="Low BP">
                            <label class="form-check-label" for="bp3">
                            Low BP
                            </label>
                        </div>
                    </div>
                </fieldset>
                <fieldset class="form-group row">
                    <legend class="col-form-label col-sm-2 float-sm-left pt-0">Sugar Level</legend>
                    <div class="col-sm-10">
                        <div class="form-check">
                            <input class="form-check-input" type="radio" name="Sugar Level" id="sugar1" value="Less than 140 mg/dL (7.8 mmol/L)" >
                            <label class="form-check-label" for="sugar1">
                            Less than 140 mg/dL (7.8 mmol/L)
                            </label>
                        </div>
                        <div class="form-check">
                            <input class="form-check-input" type="radio" name="Sugar Level" id="sugar2" value="More than 200 mg/dL (11.1 mmol/L)">
                            <label class="form-check-label" for="sugar2">
                            More than 200 mg/dL (11.1 mmol/L)
                            </label>
                        </div>
                        <div class="form-check disabled">
                            <input class="form-check-input" type="radio" name="Sugar Level" id="sugar3" value="Between 140 and 199 mg/dL (7.8 mmol/L and 11.0 mmol/L)">
                            <label class="form-check-label" for="sugar3">
                            Between 140 and 199 mg/dL (7.8 mmol/L and 11.0 mmol/L)
                            </label>
                        </div>
                    </div>
                </fieldset>
            </div>
            <div class="list-group-item">

                <h3 class="text-center mt-4">Residential Information</h3>
        
                <div class="form-group row">
                    <label for="Country" class="col-sm-2 col-form-label">Country</label>
                    <div class="col-sm-10">
                        <input type="text" class="form-control" id="Country">
                    </div>
                </div>
                <div class="form-group row">
                    <label for="State" class="col-sm-2 col-form-label">State</label>
                    <div class="col-sm-10">
                        <input type="text" class="form-control" id="State">
                    </div>
                </div>
                <div class="form-group row">
                    <label for="City" class="col-sm-2 col-form-label">City</label>
                    <div class="col-sm-10">
                        <input type="text" class="form-control" id="City">
                    </div>
                </div>
                <div class="form-group row">
                    <label for="Pin code" class="col-sm-2 col-form-label">Pin code</label>
                    <div class="col-sm-10">
                        <input type="number" class="form-control" id="Pin code">
                    </div>
                </div>

            </div>

            <div class="list-group-item">

                <h3 class="mt-4 text-center">Travel Information</h3>

                <fieldset class="form-group row">
                    <legend class="col-form-label col-sm-2 float-sm-left pt-0">Travelled before 15 days</legend>
                    <div class="col-sm-10">
                        <div class="form-check">
                            <input class="form-check-input" type="radio" name="Yes" id="travelinfo1" value="Yes" >
                            <label class="form-check-label" for="travelinfo1">
                            Yes
                            </label>
                        </div>
                        <div class="form-check">
                            <input class="form-check-input" type="radio" name="Yes" id="travelinfo2" value="No">
                            <label class="form-check-label" for="travelinfo2">
                            No
                            </label>
                        </div>
                        
                    </div>
                </fieldset>
                
                <h3 class="mt-4 text-center">Travel History</h3>

                <fieldset class="form-group row">
                    <legend class="col-form-label col-sm-2 float-sm-left pt-0">Check which ever applies</legend>
                    <div class="col-sm-10">
                        <div class="form-check form-check-inline">
                            <input class="form-check-input" type="checkbox" id="travelhis1" value="y" name="travelhis1">
                            <label class="form-check-label" for="travelhis1">International Travelling</label>
                        </div>
                        <br>
                        <div class="form-check form-check-inline">
                            <input class="form-check-input" type="checkbox" id="travelhis2" value="y" name="travelhis2">
                            <label class="form-check-label" for="travelhis2">Visited local places in your country.</label>
                        </div>
                        <br>
                        <div class="form-check form-check-inline">
                            <input class="form-check-input" type="checkbox" id="travelhis3" value="y" name="travelhis3">
                            <label class="form-check-label" for="travelhis3">Got in touch with typhoid infected person.</label>
                        </div>
                        <br>
                        <div class="form-check form-check-inline">
                            <input class="form-check-input" type="checkbox" id="travelhis4" value="y" name="travelhis4">
                            <label class="form-check-label" for="travelhis4">Used any public washroom.</label>
                        </div>
                        <br>
                        <div class="form-check form-check-inline">
                            <input class="form-check-input" type="checkbox" id="travelhis5" value="y" name="travelhis5">
                            <label class="form-check-label" for="travelhis5">Water you used is contaminated.</label>
                        </div>
                        <br>
                        <div class="form-check form-check-inline">
                            <input class="form-check-input" type="checkbox" id="travelhis6" value="y" name="travelhis6">
                            <label class="form-check-label" for="travelhis6">Consumed outside food/drinks .</label>
                        </div>
                        <br>
                        <div class="form-check form-check-inline">
                            <input class="form-check-input" type="checkbox" id="travelhis7" value="y" name="travelhis7">
                            <label class="form-check-label" for="travelhis7">Consumed any seafood.</label>
                        </div>
                        <br>
                        <div class="form-check form-check-inline">
                            <input class="form-check-input" type="checkbox" id="travelhis8" value="y" name="travelhis8">
                            <label class="form-check-label" for="travelhis8">Visited swimming pools/ beaches/ water sports.</label>
                        </div>
                        <br>
                        <div class="form-check form-check-inline">
                            <input class="form-check-input" type="checkbox" id="travelhis9" value="y" name="travelhis9">
                            <label class="form-check-label" for="travelhis9">Any Other</label>
                        </div>
                        <br>
                        <div class="form-group row">
                            <label for="Please specify other reasons" class="col-sm-2 col-form-label">Please specify other reasons</label>
                            <div class="col-sm-10">
                                <input type="text" class="form-control" id="Please specify other reasons">
                            </div>
                        </div>
                    </div>
                </fieldset>

            </div>

            <div class="list-group-item">

                <h3 class="mt-4 text-center">Previously affected</h3>
                <fieldset class="form-group row">
                    <legend class="col-form-label col-sm-2 float-sm-left pt-0">Patient previously affected with the typhoid and not cured</legend>
                    <div class="col-sm-10">
                        <div class="form-check">
                            <input class="form-check-input" type="radio" name="previouslyAffected" id="bp1" value="Yes" >
                            <label class="form-check-label" for="bp1">
                            Yes
                            </label>
                        </div>
                        <div class="form-check">
                            <input class="form-check-input" type="radio" name="previouslyAffected" id="bp2" value="No">
                            <label class="form-check-label" for="bp2">
                            No
                            </label>
                        </div>
                        
                    </div>
                </fieldset>

            </div>

            <div class="list-group-item d-none" id="showIfYes">

                <h4>If you are previously affected please fill the below details</h4>
                <fieldset class="form-group row">
                    <legend class="col-form-label col-sm-2 float-sm-left pt-0">Reasons</legend>
                    <div class="col-sm-10">
                        <div class="form-check form-check-inline">
                            <input class="form-check-input" type="checkbox" id="reasons1" value="y" name="Reasons">
                            <label class="form-check-label" for="reasons1">Not appropriate antibiotics</label>
                        </div>
                        <br>
                        <div class="form-check form-check-inline">
                            <input class="form-check-input" type="checkbox" id="reasons2" value="y" name="Reasons">
                            <label class="form-check-label" for="reasons2">Perforation</label>
                        </div>
                        <br>
                        <div class="form-check form-check-inline">
                            <input class="form-check-input" type="checkbox" id="reasons3" value="y" name="Reasons">
                            <label class="form-check-label" for="reasons3">Both </label>
                        </div>
                        <br>
                        <div class="form-check form-check-inline">
                            <input class="form-check-input" type="checkbox" id="reasons4" value="y" name="Reasons">
                            <label class="form-check-label" for="reasons4">Other reasons</label>
                        </div>
                        <br>
                    </div>
                </fieldset>       
                    
                        
                <div class="form-group row">
                    <label for="Please specify other reasons" class="col-sm-2 col-form-label">Please specify other reasons</label>
                    <div class="col-sm-10">
                        <input type="text" class="form-control" id="Please specify other reasons">
                    </div>
                </div>
            </fieldset>       
            <fieldset class="form-group row">
                <legend class="col-form-label col-sm-2 float-sm-left pt-0">Symptoms for not appropriate antibiotics </legend>
                <div class="col-sm-10">
                    <div class="form-check form-check-inline">
                        <input class="form-check-input" type="checkbox" id="aa1" value="y" name="naa">
                        <label class="form-check-label" for="aa1">Internal Bleeding</label>
                    </div>
                    <br>
                    <div class="form-check form-check-inline">
                        <input class="form-check-input" type="checkbox" id="aa2" value="y" name="naa">
                        <label class="form-check-label" for="aa2">Feeling Tired</label>
                    </div>
                    <br>
                    <div class="form-check form-check-inline">
                        <input class="form-check-input" type="checkbox" id="aa3" value="y" name="naa">
                        <label class="form-check-label" for="aa3">Pale Skin</label>
                    </div>
                    <br>
                    <div class="form-check form-check-inline">
                        <input class="form-check-input" type="checkbox" id="aa4" value="y" name="naa">
                        <label class="form-check-label" for="aa4">An Irregular Heartbeat</label>
                    </div>
                    <br>
                    <div class="form-check form-check-inline">
                        <input class="form-check-input" type="checkbox" id="aa5" value="y" name="naa">
                        <label class="form-check-label" for="aa5">Vomiting blood</label>
                    </div>
                    <br>
                    <div class="form-check form-check-inline">
                        <input class="form-check-input" type="checkbox" id="aa6" value="y" name="naa">
                        <label class="form-check-label" for="aa6">Poo [Verydark/tar-like]</label>
                    </div>
                </div>
            </fieldset>
            <fieldset class="form-group row">
                <legend class="col-form-label col-sm-2 float-sm-left pt-0">Symptoms for Perforation </legend>
                <div class="col-sm-10">
                    <div class="form-check form-check-inline">
                        <input class="form-check-input" type="checkbox" id="p1" value="y" name="paa">
                        <label class="form-check-label" for="p1">Abdominal pain</label>
                    </div>
                    <br>
                    <div class="form-check form-check-inline">
                        <input class="form-check-input" type="checkbox" id="p2" value="y" name="paa">
                        <label class="form-check-label" for="p2">Severe cramps in the stomach region</label>
                    </div>
                    <br>
                    <div class="form-check form-check-inline">
                        <input class="form-check-input" type="checkbox" id="p3" value="y" name="paa">
                        <label class="form-check-label" for="p3">Bloating, or a feeling of tightness or swelling</label>
                    </div>
                    <br>
                    <div class="form-check form-check-inline">
                        <input class="form-check-input" type="checkbox" id="p4" value="y" name="paa">
                        <label class="form-check-label" for="p4">Nausea and vomiting</label>
                    </div>
                    <br>
                    <div class="form-check form-check-inline">
                        <input class="form-check-input" type="checkbox" id="p5" value="y" name="paa">
                        <label class="form-check-label" for="p5">Bleeding from the rectum</label>
                    </div>
                    <br>
                <div class="form-group row">
                    <label for="Diet you followed" class="col-sm-2 col-form-label">Diet you followed</label>
                    <div class="col-sm-10">
                        <input type="text" class="form-control" id="Diet you followed">
                    </div>
                </div>
                <br>
                <div class="form-group row">
                    <label for="Antibiotics course days (how many days you have taken the antibiotics)" class="col-sm-2 col-form-label">Antibiotics course days (how many days you have taken the antibiotics)</label>
                    <div class="col-sm-10">
                        <input type="text" class="form-control" id="Antibiotics course days (how many days you have taken the antibiotics)">
                    </div>
                </div>
                </div>    
            </fieldset>

            </div>

            <div class="list-group-item d-none" id="showIfNo">
                <h4>If you are not previously affected please fill the below details</h4>
                <fieldset class="form-group row">
                    <legend class="col-form-label col-sm-2 float-sm-left pt-0">From how many weeks are you unwell?</legend>
                    <div class="col-sm-10">
                        <div class="form-check">
                            <input class="form-check-input" type="radio" name="week" id="un1" value="1 Week">
                            <label class="form-check-label" for="un1">
                            1 Week
                            </label>
                        </div>
                        <div class="form-check">
                            <input class="form-check-input" type="radio" name="week" id="un2" value="2 Weeks">
                            <label class="form-check-label" for="un2">
                            2 Weeks
                            </label>
                        </div>
                        <div class="form-check disabled">
                            <input class="form-check-input" type="radio" name="week" id="un3" value="3 Weeks">
                            <label class="form-check-label" for="un3">
                            3 Weeks
                            </label>
                        </div>
                        <div class="form-check disabled">
                            <input class="form-check-input" type="radio" name="week" id="un4" value="More than 3 Weeks">
                            <label class="form-check-label" for="un4">
                            More than 3 Weeks
                            </label>
                        </div>
                    </div>
                </fieldset>
                <fieldset class="form-group row">
                    <legend class="col-form-label col-sm-2 float-sm-left pt-0">Body temperature</legend>
                    <div class="col-sm-10">
                        <div class="form-check">
                            <input class="form-check-input" type="radio" name="temperature" id="temp1" value="Low">
                            <label class="form-check-label" for="temp1">
                            Low
                            </label>
                        </div>
                        <div class="form-check">
                            <input class="form-check-input" type="radio" name="temperature" id="temp2" value="Normal">
                            <label class="form-check-label" for="temp2">
                            Normal 
                            </label>
                        </div>
                        <div class="form-check disabled">
                            <input class="form-check-input" type="radio" name="temperature" id="temp3" value="High">
                            <label class="form-check-label" for="temp3">
                            High
                            </label>
                        </div>
                    </div>
                </fieldset>
                <fieldset class="form-group row">
                    <legend class="col-form-label col-sm-2 float-sm-left pt-0">Headache</legend>
                    <div class="col-sm-10">
                        <div class="form-check">
                            <input class="form-check-input" type="radio" name="Headache" id="head1" value="Yes">
                            <label class="form-check-label" for="head1">
                            Yes
                            </label>
                        </div>
                        <div class="form-check">
                            <input class="form-check-input" type="radio" name="Headache" id="head2" value="No">
                            <label class="form-check-label" for="head2">
                            No
                            </label>
                        </div>
                    </div>
                </fieldset>
                <fieldset class="form-group row">
                    <legend class="col-form-label col-sm-2 float-sm-left pt-0">Fatigue</legend>
                    <div class="col-sm-10">
                        <div class="form-check">
                            <input class="form-check-input" type="radio" name="Fatigue" id="Fat1" value="Yes">
                            <label class="form-check-label" for="Fat1">
                            Yes
                            </label>
                        </div>
                        <div class="form-check">
                            <input class="form-check-input" type="radio" name="Fatigue" id="Fat2" value="No">
                            <label class="form-check-label" for="Fat2">
                            No
                            </label>
                        </div>
                    </div>
                </fieldset>
                <fieldset class="form-group row">
                    <legend class="col-form-label col-sm-2 float-sm-left pt-0">General aches and Pains</legend>
                    <div class="col-sm-10">
                        <div class="form-check">
                            <input class="form-check-input" type="radio" name="General aches and Pains" id="gap1" value="Yes">
                            <label class="form-check-label" for="gap1">
                            Yes
                            </label>
                        </div>
                        <div class="form-check">
                            <input class="form-check-input" type="radio" name="General aches and Pains" id="gap2" value="No">
                            <label class="form-check-label" for="gap2">
                            No 
                            </label>
                        </div>
                    </div>
                </fieldset>
                <fieldset class="form-group row">
                    <legend class="col-form-label col-sm-2 float-sm-left pt-0">Cough</legend>
                    <div class="col-sm-10">
                        <div class="form-check">
                            <input class="form-check-input" type="radio" name="Cough" id="cou1" value="Dry cough">
                            <label class="form-check-label" for="cou1">
                            Dry cough
                            </label>
                        </div>
                        <div class="form-check">
                            <input class="form-check-input" type="radio" name="Cough" id="cou2" value="Wet cough">
                            <label class="form-check-label" for="cou2">
                            Wet cough
                            </label>
                        </div>
                        <div class="form-check disabled">
                            <input class="form-check-input" type="radio" name="Cough" id="cou3" value="Whopping cough">
                            <label class="form-check-label" for="cou3">
                            Whopping cough
                            </label>
                        </div>
                        <div class="form-check disabled">
                            <input class="form-check-input" type="radio" name="Cough" id="cou4" value="Choking cough">
                            <label class="form-check-label" for="cou4">
                            Choking cough
                            </label>
                        </div>
                        <div class="form-check disabled">
                            <input class="form-check-input" type="radio" name="Cough" id="cou5" value="Chronic cough">
                            <label class="form-check-label" for="cou5">
                            Chronic cough
                            </label>
                        </div>
                        <div class="form-check disabled">
                            <input class="form-check-input" type="radio" name="Cough" id="cou6" value="No cough">
                            <label class="form-check-label" for="cou6">
                            No cough
                            </label>
                        </div>
                    </div>
                </fieldset>
                <h5>If illness more than 2 weeks</h5>
                <fieldset class="form-group row">
                    <legend class="col-form-label col-sm-2 float-sm-left pt-0">Appetite</legend>
                    <div class="col-sm-10">
                        <div class="form-check">
                            <input class="form-check-input" type="radio" name="Appetite" id="appe1" value="Infected">
                            <label class="form-check-label" for="appe1">
                            Infected
                            </label>
                        </div>
                        <div class="form-check">
                            <input class="form-check-input" type="radio" name="Appetite" id="appe2" value="Not Infected">
                            <label class="form-check-label" for="appe2">
                            Not Infected 
                            </label>
                        </div>
                    </div>
                </fieldset>
                <fieldset class="form-group row">
                    <legend class="col-form-label col-sm-2 float-sm-left pt-0">Tummy ache</legend>
                    <div class="col-sm-10">
                        <div class="form-check">
                            <input class="form-check-input" type="radio" name="Tummy ache" id="tua1" value="Low">
                            <label class="form-check-label" for="tua1">
                            Low
                            </label>
                        </div>
                        <div class="form-check">
                            <input class="form-check-input" type="radio" name="Tummy ache" id="tua2" value="Normal">
                            <label class="form-check-label" for="tua2">
                            Normal 
                            </label>
                        </div>
                        <div class="form-check disabled">
                            <input class="form-check-input" type="radio" name="Tummy ache" id="tua3" value="High">
                            <label class="form-check-label" for="tua3">
                            High
                            </label>
                        </div>
                    </div>
                </fieldset>
                <fieldset class="form-group row">
                    <legend class="col-form-label col-sm-2 float-sm-left pt-0">Diarrhea</legend>
                    <div class="col-sm-10">
                        <div class="form-check">
                            <input class="form-check-input" type="radio" name="Diarrhea" id="dia1" value="Yes">
                            <label class="form-check-label" for="dia1">
                            Yes
                            </label>
                        </div>
                        <div class="form-check">
                            <input class="form-check-input" type="radio" name="Diarrhea" id="dia2" value="No">
                            <label class="form-check-label" for="dia2">
                            No 
                            </label>
                        </div>
                    </div>
                </fieldset>
                <fieldset class="form-group row">
                    <legend class="col-form-label col-sm-2 float-sm-left pt-0">Rashes</legend>
                    <div class="col-sm-10">
                        <div class="form-check">
                            <input class="form-check-input" type="radio" name="Rashes" id="rash1" value="Yes">
                            <label class="form-check-label" for="rash1">
                            Yes
                            </label>
                        </div>
                        <div class="form-check">
                            <input class="form-check-input" type="radio" name="Rashes" id="rash2" value="No">
                            <label class="form-check-label" for="rash2">
                            No
                            </label>
                        </div>
                    </div>
                </fieldset>
                <fieldset class="form-group row">
                    <legend class="col-form-label col-sm-2 float-sm-left pt-0">Vomitings</legend>
                    <div class="col-sm-10">
                        <div class="form-check">
                            <input class="form-check-input" type="radio" name="Vomitings" id="vom1" value="Frequent">
                            <label class="form-check-label" for="vom1">
                            Frequent
                            </label>
                        </div>
                        <div class="form-check">
                            <input class="form-check-input" type="radio" name="Vomitings" id="vom2" value="Not Frequent">
                            <label class="form-check-label" for="vom2">
                            Not Frequent
                            </label>
                        </div>
                    </div>
                </fieldset>
                <fieldset class="form-group row">
                    <legend class="col-form-label col-sm-2 float-sm-left pt-0">Swollen stomach</legend>
                    <div class="col-sm-10">
                        <div class="form-check">
                            <input class="form-check-input" type="radio" name="Swollen stomach" id="swo1" value="Low">
                            <label class="form-check-label" for="swo1">
                            Yes
                            </label>
                        </div>
                        <div class="form-check">
                            <input class="form-check-input" type="radio" name="Swollen stomach" id="swo2" value="Normal">
                            <label class="form-check-label" for="swo2">
                            No
                            </label>
                        </div>
                    </div>
                </fieldset>

                
            </div>
        </ul>

        <div class="card-footer">
            <button type="submit" class="btn btn-primary btn-lg btn-block">Submit</button>
        </div>
    </div>


    <script src="https://cdn.jsdelivr.net/npm/jquery@3.5.1/dist/jquery.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.1/dist/js/bootstrap.bundle.min.js" integrity="sha384-fQybjgWLrvvRgtW6bFlB7jaZrFsaBXjsOMm/tB9LTS58ONXgqbR9W8oWht/amnpF" crossorigin="anonymous"></script>
    
    <script>
        const form = document.forms['google-sheet'];
        var dependency = form.previouslyAffected;
        var showIfYes = document.getElementById('showIfYes');
        var showIfNo = document.getElementById('showIfNo');

        form.onchange = (e) => {

            if (dependency.value == "Yes") {
                showIfYes.classList.remove("d-none");
                showIfNo.classList.add("d-none");
            } else {
                showIfYes.classList.add("d-none");
                showIfNo.classList.remove("d-none");
            }
        }



        // const scriptURL = '';
        form.addEventListener('submit', e => {
        e.preventDefault();
        alert("Form Submitted!");
            fetch(scriptURL, { method: 'POST', body: new FormData(form)})
                .then(response => alert("Thanks for Contacting us..! We Will Contact You Soon..."))
                .catch(error => console.error('Error!', error.message))
            
            form.reset();
        })

    </script>

</body>
</html>
