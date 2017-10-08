<!DOCTYPE html>
<html lang="en">
<head>
  <title>BattPKT</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
  <script src="https://cdn.netpie.io/microgear.js"></script>
  <script src="raphael-2.1.4.min.js"></script>
  <script src="justgage.js"></script>
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js"></script>
  <script src="https://www.google.com/jsapi"></script>
  <!-- <script src="weather-icons.min.css"></script> -->
  <link href="https://gitcdn.github.io/bootstrap-toggle/2.2.2/css/bootstrap-toggle.min.css" rel="stylesheet">
  <script src="https://gitcdn.github.io/bootstrap-toggle/2.2.2/js/bootstrap-toggle.min.js"></script>
  <!-- Latest compiled and minified CSS -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/bootstrap-select/1.12.1/css/bootstrap-select.min.css">

  <!-- Latest compiled and minified JavaScript -->
  <script src="https://cdnjs.cloudflare.com/ajax/libs/bootstrap-select/1.12.1/js/bootstrap-select.min.js"></script>

  <!-- (Optional) Latest compiled and minified JavaScript translation files -->
  <script src="https://cdnjs.cloudflare.com/ajax/libs/bootstrap-select/1.12.1/js/i18n/defaults-*.min.js"></script>
  <script src="https://www.gstatic.com/firebasejs/4.5.0/firebase.js"></script>
  <script src="https://cdn.firebase.com/js/client/2.4.2/firebase.js"></script>
  <script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyDL-cRJzy6WSOSsAymv_8WurQmtO54NXzA"></script>
  <!-- <script src="http://ajax.aspnetcdn.com/ajax/jQuery/jquery-1.10.1.min.js"></script> -->
  <style>
table, td {
    border: 1px solid black;
}
</style>
</head>
<body>
        <!-- <div class="form-group row">
          <label for="example-date-input" class="col-2 col-form-label">Date</label>
          <div class="col-10">
            <input class="form-control" type="date" value="2017-10-6" id="example-date-input">
          </div>
        </div> -->
        <div class="row">
          <div class="col-lg-12">
            <h1 class="page-header">
            Data <small>Battery EN-PKT</small>
            </h1>
            <ol class="breadcrumb">
              <li class="active">
                <i class="fa fa-dashboard"></i> Table
              </li>
            </ol>
          </div>
        </div>
        <div class="row">     
            <div class="col-xs-4">
            </div>
            <div class="col-xs-2">
              <input class="form-control" type="date" id="search">
            </div>
            <div class="col-xs-2">
              <button type="button" class="btn btn-success" id="btnbatt" onclick="myDeleteFunction()">Press</button>
               <!-- <button type="button" class="btn btn-success" id="btndel" onclick="myDeleteFunction()"> Clear</button> -->

            </div>
            <div class="col-xs-4">
            <p id="presentationconnect"></p>
            </div>
        </div>
        <div class="row">     
            <div class="col-xs-12">
            <br>
            </div>
        </div>
        <div class="container">
         <table id="myTable" class="table table-bordered">

            <td><center>Site Code<center></td>
            <td><center>C1 Install Data<center></td>
            <td><center>C2 Install Data<center></td>
            <td><center>C3 Install Data<center></td>
        </table>
        </div>
        <ul></ul>
      <script type="text/javascript">
       // Initialize Firebase
       var config = {
        apiKey: "AIzaSyBKTGzNHS0BTljPKDs3UIBuahIpV81WZZQ",
        authDomain: "battpkt.firebaseapp.com",
        databaseURL: "https://battpkt.firebaseio.com",
        projectId: "battpkt",
        storageBucket: "battpkt.appspot.com",
        messagingSenderId: "272172803569"
      };
      firebase.initializeApp(config);
        var rootRef = firebase.database().ref();
        var database = firebase.database();
      </script>
      <script type="text/javascript">
        var k=0;
       function getdata(datafromuser){

        var databatt = new Firebase("https://battpkt.firebaseio.com/");
        databatt.orderByValue().on("value", function(snapshot) {

          snapshot.forEach(function(data) {
              // console.log(data.val().Name);
              // console.log(data.val().C1.install);
              // var databatts = [data.val().Name, data.val().C1.install];
              // console.log(databatts);
              var year = Number(datafromuser.substring(0,4));
              var month = Number(datafromuser.substring(5,7));
              var day = Number(datafromuser.substring(8,datafromuser.length));
              // console.log(day);
              // console.log(month);
              // console.log(year);
              // var store[];
              // console.log(day);
              // var sentstore=""
              var sentTostore = [];
              var count=0;
              var databatts = snapshotToArray(data);
              // sentstore+=databatts[(databatts.length-1)]
              for (i = 0; i < databatts.length; i++){

                if(databatts[i][2] == "/"){
                  var DayData = Number(databatts[i].substring(0,2))
                  var MonthData = Number(databatts[i].substring(3,5))
                  var YearData = Number(databatts[i].substring(6,10))
                  YearData+=3;

                  console.log("Number(YearData)"+YearData)
                  console.log("Number(MonthData)"+MonthData)
                  console.log("Number(DayData)"+DayData)

                  diffy = YearData-year
                  diffm = MonthData-month
                  diffd = DayData-day

                  console.log("diffd"+diffd)
                  console.log("diffm"+diffm)
                  console.log("diffy"+diffy)

                  if(diffy<0){
                   sentTostore.push(databatts[i]);
                  }
                  else if(diffy==0 && diffm<0){
                   sentTostore.push(databatts[i]);
                  //  if(diffd <= 0)
                  //   sentTostore.push(databatts[i]);
                  // else sentTostore.push("No Data");
                  }
                  else if(diffy==0 && diffm<=0 && diffd <= 0)
                  sentTostore.push(databatts[i]);
                  
                  // sentstore+=","
                  // sentstore+=databatts[i];
                  else sentTostore.push("No Data");
                }
                else 
                  sentTostore.push(databatts[i]);
              }
              // console.log("count="+count)
              count = i

              console.log("count="+count)
              console.log(sentTostore)
              var Ddatabatts = databatts[0];
              // var Mdatabatts = 
              // var Ydatabatts = 
              // console.log(k)
              myFunction(sentTostore,count);
              // document.getElementById("show").innerHTML = databatts
              // for (i = 0; i < databatts.length; i++) { 
              //   console.log(databatts[i]);
                // store[i]=databatts[i];
                // myFunction(databatts[i]);
                // console.log("----------");
                // document.getElementById("Timepredicpy").innerHTML = databatts[i]
                  // if(i = (databatts.length)){
                  //   myFunction(databatts);
                  // }
                // }    
            });
        });
      };
      </script>

      <script type="text/javascript">
        function arraypush(data){

        }
        function snapshotToArray(snapshot) {
        var returnArr = [];

        snapshot.forEach(function(childSnapshot) {
        var item = childSnapshot.val();
        item.key = childSnapshot.key;

        returnArr.push(item);
        // console.log(returnArr);
         });

        return returnArr;
        // console.log(returnArr);
    };
      </script>
      <script type="text/javascript">
        document.getElementById('btnbatt').addEventListener('click', function() {
          var input = document.getElementById("search");
          var inputt =  search.value;
          // console.log(inputt);
          var dates = String(inputt);
          console.log(dates);
          getdata(dates);
        });
      </script>
      <script type="text/javascript">
        function myFunction(datainsert,cul) {
          var lengthofdata = datainsert.length-1;
          console.log(lengthofdata)
          var xx  =[]
          var checkdarray=0;
          var cell = [];
          var table = document.getElementById("myTable");
          // if((datainsert[0] != "No Data") || (datainsert[1] != "No Data")){
          // var row = table.insertRow(1); 
          // var cell1 = row.insertCell(0);
          // var cell2 = row.insertCell(1);
          // var cell3 = row.insertCell(2);
          for(i=0;i<=lengthofdata;i++){
            if(datainsert[i] != "No Data"){
              xx[i] = 1
              checkdarray+=1;
            }
            else
              xx[i] = 0
          }

          console.log("xx="+xx)
          if(checkdarray>1){
            var row = table.insertRow(1); 
            cell[0] = row.insertCell(0);
            cell[1] = row.insertCell(1);
            cell[2] = row.insertCell(2);
            cell[3]= row.insertCell(3);
            cell[0].innerHTML=datainsert[lengthofdata]
            // if(xx[lengthofdata-3]=="1")
            //    var cell2 = row.insertCell(lengthofdata-3);
            // if(xx[lengthofdata-2]=="1")
            //    var cell3 = row.insertCell(lengthofdata-2);
            // if(xx[lengthofdata-1]=="1")
            //    var cell4 = row.insertCell(lengthofdata-1);
          }
          for(i=0;i<lengthofdata;i++){
            if(xx[i]=="1"){
              // cell[i+1] = row.insertCell(i);
              cell[i+1].innerHTML=datainsert[i]
              k+=1
            }

          }


          // while(lengthofdata>=0){
          //    if(xx[lengthofdata]=="1"){
          //     cell[0].innerHTML=datainsert[lengthofdata-lengthofdata]
          //     console.log("Name")
          // }
         
          
          // if((datainsert[lengthofdata-1] != "No Data") || (datainsert[lengthofdata-2] != "No Data") || (datainsert[lengthofdata-3] != "No Data"))
          // {
          // var row = table.insertRow(1); 
          // var cell1 = row.insertCell(0);
          // var cell2 = row.insertCell(1);
          // var cell3 = row.insertCell(2);
          // var cell4 = row.insertCell(3);
          // cell1.innerHTML = datainsert[lengthofdata];
          // }
          
          // if((datainsert[0] != "No Data") && (datainsert[0][2] == "/")){
          //  cell2.innerHTML = datainsert[0]; 
          //  k+=1
          // }
          
          
          // if((datainsert[1] != "No Data") && (datainsert[1][2] == "/")){
          //   cell3.innerHTML = datainsert[1];
          // k+=1
          // }

          // if((datainsert[2] != "No Data") && (datainsert[2][2] == "/")){
          //  cell3.innerHTML = datainsert[]; 
          //  k+=1
          // }


          // if(datainsert[1][2] != "/"){
          //   cell1.innerHTML = datainsert[1];
          // }

          // if(datainsert[1][2] != "/")
          //   cell1.innerHTML=datainsert[1]
          // if(datainsert[2][2] != "/"){
          // cell1.innerHTML = datainsert[2];
          // }
          // if(datainsert[2][2] == "/"){
          // var cell4 = row.insertCell(2);
          // cell4.innerHTML = datainsert[2]; 
          // k+=1
          // cell1.innerHTML = datainsert[3];

          // }
          
          
          

          // }
          // // cell1.innerHTML = datainsert[2];
          // // if(datainsert[0] != "No Data")
          // // cell2.innerHTML = datainsert[0];
          // // if(datainsert[1] != "No Data")
          // // cell3.innerHTML = datainsert[1];
          // console.log("k= "+k)
          // // document.getElementById("presentationconnect").innerHTML = k 
          document.getElementById("presentationconnect").innerHTML = " Sum of Value : "+k 
          
        }
        function myDeleteFunction() {
        var del=k;
        for(i=0 ; i<del; i++){
        document.getElementById("myTable").deleteRow(1);
        k=0;
        }
        
      }
      </script>
</body>
</html>